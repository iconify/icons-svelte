<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpfg2hbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpfg2hbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-fill" {...props}></Icon>
