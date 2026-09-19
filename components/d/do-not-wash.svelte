<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywk2o2cwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":496};
const content = `<path class="ywk2o2cwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:do-not-wash" {...props}></Icon>
