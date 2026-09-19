<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw7tdp1nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw7tdp1nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-remote" {...props}></Icon>
