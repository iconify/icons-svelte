<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0hziwb9d.css';
import '../../css/x/x47f5ib6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0hziwb9d"/><path class="x47f5ib6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rin" {...props}></Icon>
