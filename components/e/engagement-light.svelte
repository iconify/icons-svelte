<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0awb8bkd.css';
import '../../css/e/ejcigpbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0awb8bkd"/><path class="ejcigpbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:engagement-light" {...props}></Icon>
