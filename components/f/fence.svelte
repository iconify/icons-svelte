<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh05vbo4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh05vbo4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fence" {...props}></Icon>
