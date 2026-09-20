<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a79_kzbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a79_kzbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mail-16" {...props}></Icon>
