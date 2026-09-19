<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwcxw0bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bwcxw0bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-sad-fill-16" {...props}></Icon>
