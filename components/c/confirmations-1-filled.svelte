<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyuoiib2w.css';
import '../../css/b/b6kmhlhnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyuoiib2w"/><path clip-rule="evenodd" class="b6kmhlhnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-1-filled" {...props}></Icon>
