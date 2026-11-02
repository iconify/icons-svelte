<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjxcwxqyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjxcwxqyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bowl-line" {...props}></Icon>
