<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtsz_ig2m.css';
import '../../css/c/cgvv3fb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qtsz_ig2m"/><path class="cgvv3fb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:research-bloch-sphere" {...props}></Icon>
