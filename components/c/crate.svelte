<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oquswcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oquswcb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:crate" {...props}></Icon>
