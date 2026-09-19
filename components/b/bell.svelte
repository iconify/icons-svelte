<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ow_cbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8ow_cbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bell" {...props}></Icon>
