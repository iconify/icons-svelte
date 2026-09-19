<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vot768pgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":497,"height":512};
const content = `<path class="vot768pgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:powerbuilder" {...props}></Icon>
