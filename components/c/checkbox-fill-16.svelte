<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvhjv7b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tvhjv7b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:checkbox-fill-16" {...props}></Icon>
