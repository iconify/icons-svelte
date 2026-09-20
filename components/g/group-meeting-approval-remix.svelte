<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gobjw1bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gobjw1bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:group-meeting-approval-remix" {...props}></Icon>
