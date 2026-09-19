<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esgs_iocj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="esgs_iocj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-curl-small" {...props}></Icon>
