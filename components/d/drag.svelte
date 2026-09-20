<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcq0ozbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kcq0ozbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:drag" {...props}></Icon>
