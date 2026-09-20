<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7b8ribgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7b8ribgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:issues-reopen-line" {...props}></Icon>
