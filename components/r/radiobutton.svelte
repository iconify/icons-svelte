<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipt8wobsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ipt8wobsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:radiobutton" {...props}></Icon>
