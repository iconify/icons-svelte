<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0am-ac5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h0am-ac5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-premiere-filled" {...props}></Icon>
