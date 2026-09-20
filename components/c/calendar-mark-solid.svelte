<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4aprabcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p4aprabcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:calendar-mark-solid" {...props}></Icon>
