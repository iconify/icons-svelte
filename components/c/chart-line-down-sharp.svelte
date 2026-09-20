<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhiqf8q1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhiqf8q1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-down-sharp" {...props}></Icon>
