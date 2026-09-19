<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4keo0bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r4keo0bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:college-hoops" {...props}></Icon>
