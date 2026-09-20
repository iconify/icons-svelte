<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoqu0cb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xoqu0cb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nutalert-light" {...props}></Icon>
