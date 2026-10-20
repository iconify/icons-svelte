<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy-u42bhp.css';
import '../../css/n/nwipklbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zy-u42bhp"/><path class="nwipklbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-heart-48-bold" {...props}></Icon>
