<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6su4bex.css';
import '../../css/o/ogcp94bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6su4bex"/><path clip-rule="evenodd" class="ogcp94bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mention-square-bold" {...props}></Icon>
