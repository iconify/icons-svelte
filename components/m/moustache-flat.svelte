<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w848efbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w848efbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:moustache-flat" {...props}></Icon>
