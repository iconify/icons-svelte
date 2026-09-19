<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7q6albzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c7q6albzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:closed-mailbox-lowered-flag" {...props}></Icon>
