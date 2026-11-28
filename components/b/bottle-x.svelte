<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob5_q808q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob5_q808q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bottle-x" {...props}></Icon>
