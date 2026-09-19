<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ols8qwbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ols8qwbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:party" {...props}></Icon>
