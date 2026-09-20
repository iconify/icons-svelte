<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2ep6s3fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w2ep6s3fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:apps" {...props}></Icon>
