<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waqc77b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="waqc77b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus-20-solid" {...props}></Icon>
