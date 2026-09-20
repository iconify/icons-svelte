<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in4lh2aet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="in4lh2aet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:qr-code-solid" {...props}></Icon>
