<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd5nq7b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qd5nq7b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-left" {...props}></Icon>
