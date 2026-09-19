<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb42qelyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qb42qelyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-decrease-stroke-12" {...props}></Icon>
