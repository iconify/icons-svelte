<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk3pjmb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qk3pjmb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bike" {...props}></Icon>
