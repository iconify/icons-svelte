<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inzdrrbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":367,"height":512};
const content = `<path class="inzdrrbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mermaid" {...props}></Icon>
