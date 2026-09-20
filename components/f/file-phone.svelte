<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9411hbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9411hbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-phone" {...props}></Icon>
