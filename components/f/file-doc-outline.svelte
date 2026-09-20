<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5oe7jbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v5oe7jbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-doc-outline" {...props}></Icon>
