<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx9uqla7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qx9uqla7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:boot" {...props}></Icon>
