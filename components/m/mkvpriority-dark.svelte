<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6_yb2boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c6_yb2boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mkvpriority-dark" {...props}></Icon>
