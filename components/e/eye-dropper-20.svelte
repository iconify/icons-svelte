<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9zishbhy.css';
import '../../css/j/j344wacyx.css';
import '../../css/c/cti30rbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9zishbhy"/><path class="j344wacyx"/><path class="cti30rbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-dropper-20" {...props}></Icon>
