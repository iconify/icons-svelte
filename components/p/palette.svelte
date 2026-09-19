<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4iqprvyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4iqprvyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:palette" {...props}></Icon>
