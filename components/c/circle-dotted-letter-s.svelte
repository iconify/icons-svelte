<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma2b6-b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2b6-b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-s" {...props}></Icon>
