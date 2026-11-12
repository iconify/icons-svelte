<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmi3aw10y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmi3aw10y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-heart" {...props}></Icon>
