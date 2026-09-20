<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mijns_5go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mijns_5go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align-left-justify" {...props}></Icon>
