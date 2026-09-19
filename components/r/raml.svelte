<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa3ux0u-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":437,"height":512};
const content = `<path class="aa3ux0u-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:raml" {...props}></Icon>
