<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsn8jgaeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="bsn8jgaeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:egg" {...props}></Icon>
