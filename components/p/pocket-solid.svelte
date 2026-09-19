<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7knxr4qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7knxr4qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pocket-solid" {...props}></Icon>
