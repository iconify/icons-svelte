<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iav0iacja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iav0iacja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notification-application-1-remix" {...props}></Icon>
