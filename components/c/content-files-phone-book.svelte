<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2jtlbtwq.css';
import '../../css/y/ykfflpb5w.css';
import '../../css/o/oakfhh70e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c2jtlbtwq"/><path class="ykfflpb5w"/><path class="oakfhh70e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-phone-book" {...props}></Icon>
