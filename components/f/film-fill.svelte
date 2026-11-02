<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yihsg2t7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yihsg2t7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:film-fill" {...props}></Icon>
