<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl_wadqxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cl_wadqxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mozilla-firefox" {...props}></Icon>
