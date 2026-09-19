<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dte1lf23o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="dte1lf23o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:camping" {...props}></Icon>
