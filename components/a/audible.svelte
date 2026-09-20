<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq1tg9h7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jq1tg9h7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audible" {...props}></Icon>
