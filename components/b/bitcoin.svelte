<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-g6nkb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-g6nkb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bitcoin" {...props}></Icon>
