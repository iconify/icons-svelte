<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvt5o2b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qvt5o2b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send-reply-all-remix" {...props}></Icon>
