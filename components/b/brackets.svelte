<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysfr6k0aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysfr6k0aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:brackets" {...props}></Icon>
