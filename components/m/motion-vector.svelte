<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jak2suhvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jak2suhvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:motion-vector" {...props}></Icon>
