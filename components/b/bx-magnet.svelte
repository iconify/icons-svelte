<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud904hvzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud904hvzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-magnet" {...props}></Icon>
