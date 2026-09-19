<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8hgrvbws.css';
import '../../css/q/qagm_33vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a8hgrvbws"/><path class="qagm_33vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bottles-container" {...props}></Icon>
