<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9eme7ben.css';
import '../../css/b/bruiaybse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9eme7ben"/><path class="bruiaybse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-snowfall-bold" {...props}></Icon>
