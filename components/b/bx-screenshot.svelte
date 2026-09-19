<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yob1mji4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yob1mji4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-screenshot" {...props}></Icon>
