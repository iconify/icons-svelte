<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrg1gybxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrg1gybxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-tick" {...props}></Icon>
