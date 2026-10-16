<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itmoa867s.css';
import '../../css/n/nhhca1beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itmoa867s"/><path class="nhhca1beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-dots-20" {...props}></Icon>
