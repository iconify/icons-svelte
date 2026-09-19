<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9mn9rbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9mn9rbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:archive-box" {...props}></Icon>
