<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2u5p3b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2u5p3b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:caret-down-square" {...props}></Icon>
