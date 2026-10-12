<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qklghdczf.css';
import '../../css/o/olpeleb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qklghdczf"/><path class="olpeleb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:acorn-20" {...props}></Icon>
