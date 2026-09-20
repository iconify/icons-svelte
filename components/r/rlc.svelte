<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya-e6tb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-e6tb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rlc" {...props}></Icon>
