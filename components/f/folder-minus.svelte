<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw-p7j4rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-p7j4rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-minus" {...props}></Icon>
