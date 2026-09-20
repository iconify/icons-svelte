<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh9zi52ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh9zi52ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-5-box-outline" {...props}></Icon>
