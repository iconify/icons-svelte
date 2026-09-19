<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob2r7obdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ob2r7obdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-ss02" {...props}></Icon>
