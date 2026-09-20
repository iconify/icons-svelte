<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuqt_yb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:circle" {...props}></Icon>
