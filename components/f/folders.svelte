<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk_n3_4jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_n3_4jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folders" {...props}></Icon>
