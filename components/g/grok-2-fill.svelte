<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f05twi73b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f05twi73b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grok-2-fill" {...props}></Icon>
