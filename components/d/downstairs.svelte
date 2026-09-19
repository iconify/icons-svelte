<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydd9u8zty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydd9u8zty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:downstairs" {...props}></Icon>
