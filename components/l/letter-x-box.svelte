<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh5rhibls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5rhibls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-x-box" {...props}></Icon>
