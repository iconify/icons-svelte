<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prid3u2wn.css';
import '../../css/w/wcr5_ubdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prid3u2wn secondary"/><path class="primary wcr5_ubdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mustache-duo" {...props}></Icon>
