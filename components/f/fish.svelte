<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7r761b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o7r761b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fish" {...props}></Icon>
