<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2-2dm4yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e2-2dm4yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cat-face" {...props}></Icon>
