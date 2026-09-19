<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae8cvcbjo.css';
import '../../css/z/zdxltopzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ae8cvcbjo"/><path class="zdxltopzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:openstack-wordmark" {...props}></Icon>
