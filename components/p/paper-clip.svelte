<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ossn1lbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ossn1lbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:paper-clip" {...props}></Icon>
