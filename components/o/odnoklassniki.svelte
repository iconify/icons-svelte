<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chpo8u4lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":272,"height":432};
const content = `<path class="chpo8u4lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:odnoklassniki" {...props}></Icon>
