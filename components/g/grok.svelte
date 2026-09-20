<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgj0rn0ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgj0rn0ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grok" {...props}></Icon>
