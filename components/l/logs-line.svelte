<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzq88fb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzq88fb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:logs-line" {...props}></Icon>
