<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de5mf_2cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="de5mf_2cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:dial-16" {...props}></Icon>
