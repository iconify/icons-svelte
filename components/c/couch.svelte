<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afjig_b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="afjig_b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:couch" {...props}></Icon>
