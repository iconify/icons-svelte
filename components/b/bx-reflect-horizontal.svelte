<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epbc514ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epbc514ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-reflect-horizontal" {...props}></Icon>
