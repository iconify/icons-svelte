<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5r6hkb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5r6hkb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:christmas-lights" {...props}></Icon>
