<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7hgx0blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="z7hgx0blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:error" {...props}></Icon>
