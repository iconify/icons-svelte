<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5jxwb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai5jxwb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linear-line" {...props}></Icon>
