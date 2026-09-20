<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw9a3mbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw9a3mbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-minus" {...props}></Icon>
