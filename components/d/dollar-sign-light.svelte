<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxpl77h-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxpl77h-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:dollar-sign-light" {...props}></Icon>
