<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgnyjo9hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgnyjo9hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:curtain-line" {...props}></Icon>
