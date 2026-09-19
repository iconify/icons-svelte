<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6o8qlotm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x6o8qlotm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:chess-queen" {...props}></Icon>
