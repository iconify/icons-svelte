<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eozc8fbep.css';
import '../../css/l/lsxdb1s3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eozc8fbep"/><path class="lsxdb1s3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:reference-existing-ltr" {...props}></Icon>
