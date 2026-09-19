<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca8qu3aws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ca8qu3aws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-center-fill-16" {...props}></Icon>
