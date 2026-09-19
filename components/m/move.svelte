<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grm9hxbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grm9hxbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:move" {...props}></Icon>
