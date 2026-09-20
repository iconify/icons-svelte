<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vevmjxb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vevmjxb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:blox" {...props}></Icon>
