<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1zgz_b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q1zgz_b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-right-fill" {...props}></Icon>
