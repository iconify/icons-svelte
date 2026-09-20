<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg44-slrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg44-slrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:dollar-sign-solid" {...props}></Icon>
