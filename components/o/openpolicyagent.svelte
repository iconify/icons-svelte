<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi0-grw5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":460,"height":512};
const content = `<path class="hi0-grw5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openpolicyagent" {...props}></Icon>
