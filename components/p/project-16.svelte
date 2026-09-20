<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxv1afqss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pxv1afqss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-16" {...props}></Icon>
