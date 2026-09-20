<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhzl3fo_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhzl3fo_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bamboo" {...props}></Icon>
