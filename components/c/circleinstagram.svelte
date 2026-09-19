<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg-l0fbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pg-l0fbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleinstagram" {...props}></Icon>
