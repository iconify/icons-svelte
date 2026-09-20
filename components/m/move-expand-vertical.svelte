<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajpwr3bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpwr3bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:move-expand-vertical" {...props}></Icon>
