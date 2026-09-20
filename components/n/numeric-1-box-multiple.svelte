<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im1zh4btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im1zh4btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-1-box-multiple" {...props}></Icon>
