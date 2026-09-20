<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drt20ub7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="drt20ub7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-tray-1" {...props}></Icon>
