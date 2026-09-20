<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1___qv1l.css';
import '../../css/l/lsxdb1s3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q1___qv1l"/><path class="lsxdb1s3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:articles-search-ltr" {...props}></Icon>
