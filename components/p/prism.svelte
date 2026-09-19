<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hod51dubu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hod51dubu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:prism" {...props}></Icon>
