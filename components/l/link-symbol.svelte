<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfw8wabap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wfw8wabap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:link-symbol" {...props}></Icon>
