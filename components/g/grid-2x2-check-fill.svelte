<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okfw9lw1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okfw9lw1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2x2-check-fill" {...props}></Icon>
