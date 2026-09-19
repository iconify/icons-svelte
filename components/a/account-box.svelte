<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccepjikki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ccepjikki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:account-box" {...props}></Icon>
