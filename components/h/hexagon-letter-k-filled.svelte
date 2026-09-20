<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhpeq6_wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhpeq6_wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-k-filled" {...props}></Icon>
