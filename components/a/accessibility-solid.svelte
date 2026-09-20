<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyd6nsb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyd6nsb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:accessibility-solid" {...props}></Icon>
