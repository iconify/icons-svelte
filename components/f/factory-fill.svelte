<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9_rs5b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9_rs5b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:factory-fill" {...props}></Icon>
