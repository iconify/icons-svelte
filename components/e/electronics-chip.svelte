<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxk7qdb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxk7qdb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:electronics-chip" {...props}></Icon>
