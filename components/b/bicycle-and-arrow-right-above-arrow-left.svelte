<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud1hjccqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ud1hjccqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-arrow-right-above-arrow-left" {...props}></Icon>
