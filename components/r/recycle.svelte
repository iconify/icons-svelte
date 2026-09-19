<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbylo6bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qbylo6bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:recycle" {...props}></Icon>
