<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajsn0ftzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajsn0ftzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:divide" {...props}></Icon>
