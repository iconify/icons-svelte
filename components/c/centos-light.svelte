<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-brn9h0g.css';
import '../../css/q/q7y6lrbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-brn9h0g"/><path class="q7y6lrbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:centos-light" {...props}></Icon>
