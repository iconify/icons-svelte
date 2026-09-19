<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5mf1ybrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5mf1ybrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:file" {...props}></Icon>
