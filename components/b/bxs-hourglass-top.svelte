<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6rsmze0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6rsmze0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hourglass-top" {...props}></Icon>
