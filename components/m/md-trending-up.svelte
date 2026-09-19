<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t77st-b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t77st-b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-trending-up" {...props}></Icon>
