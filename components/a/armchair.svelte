<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuaegz5hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuaegz5hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:armchair" {...props}></Icon>
