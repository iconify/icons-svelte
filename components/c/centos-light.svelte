<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-brn9h0g.css';
import '../../css/k/kceoj0bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-brn9h0g"/><path class="kceoj0bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:centos-light" {...props}></Icon>
