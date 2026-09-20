<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o05y2fgyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o05y2fgyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arow-to-down-fill" {...props}></Icon>
