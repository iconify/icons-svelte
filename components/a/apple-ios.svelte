<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be5_n7dba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be5_n7dba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-ios" {...props}></Icon>
