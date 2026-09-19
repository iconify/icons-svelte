<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqr03cb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xqr03cb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-arrow-down-square" {...props}></Icon>
