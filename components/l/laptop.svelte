<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxckspbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="oxckspbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:laptop" {...props}></Icon>
