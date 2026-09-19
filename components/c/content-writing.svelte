<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds2fz5baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds2fz5baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:content-writing" {...props}></Icon>
