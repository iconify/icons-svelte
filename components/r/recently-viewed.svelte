<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnmne6b8u.css';
import '../../css/b/bsqtkvrgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dnmne6b8u"/><path class="bsqtkvrgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:recently-viewed" {...props}></Icon>
