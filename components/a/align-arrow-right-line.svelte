<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai40zdbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai40zdbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-right-line" {...props}></Icon>
