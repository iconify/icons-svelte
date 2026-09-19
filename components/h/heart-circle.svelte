<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3roe6gyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="l3roe6gyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:heart-circle" {...props}></Icon>
