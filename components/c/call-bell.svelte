<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoxm453wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoxm453wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:call-bell" {...props}></Icon>
