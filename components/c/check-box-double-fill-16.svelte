<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4f4nn3zt.css';
import '../../css/c/c25131bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c4f4nn3zt"/><path class="c25131bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-box-double-fill-16" {...props}></Icon>
