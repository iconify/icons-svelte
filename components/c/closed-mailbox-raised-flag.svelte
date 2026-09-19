<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7f1au4gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q7f1au4gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:closed-mailbox-raised-flag" {...props}></Icon>
