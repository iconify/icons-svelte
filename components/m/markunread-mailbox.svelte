<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-7gfo8if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":472};
const content = `<path class="h-7gfo8if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:markunread-mailbox" {...props}></Icon>
