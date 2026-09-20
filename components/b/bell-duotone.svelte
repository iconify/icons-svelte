<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f47fbkbfi.css';
import '../../css/z/z8ew59bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f47fbkbfi"/><path class="z8ew59bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:bell-duotone" {...props}></Icon>
