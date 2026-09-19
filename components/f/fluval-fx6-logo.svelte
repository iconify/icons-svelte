<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5e2rrbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5e2rrbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fluval-fx6-logo" {...props}></Icon>
