<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijldeqbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijldeqbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-left-middle-filled" {...props}></Icon>
