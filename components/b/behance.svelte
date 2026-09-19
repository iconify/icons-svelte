<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv82ee2qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv82ee2qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:behance" {...props}></Icon>
