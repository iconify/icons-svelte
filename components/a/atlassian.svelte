<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1qjz2bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f1qjz2bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:atlassian" {...props}></Icon>
