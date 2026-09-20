<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uet_h9nyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uet_h9nyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:css" {...props}></Icon>
