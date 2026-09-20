<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqkec9sqi.css';
import '../../css/g/gun75xfbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yqkec9sqi"/><circle class="gun75xfbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dex-auth" {...props}></Icon>
