<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm4ts6b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hm4ts6b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:folder" {...props}></Icon>
