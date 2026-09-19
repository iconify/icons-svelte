<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvcsodb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcsodb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-collapse-horizontal" {...props}></Icon>
