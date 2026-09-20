<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxjd1fbyi.css';
import '../../css/v/vdot4tock.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxjd1fbyi"/><path class="vdot4tock"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:inbox-light" {...props}></Icon>
