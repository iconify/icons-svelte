<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzu4lnr2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qzu4lnr2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:corner-top-right" {...props}></Icon>
