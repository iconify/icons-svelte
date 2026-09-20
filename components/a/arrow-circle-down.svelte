<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuqt_yb-q.css';
import '../../css/x/x6yv7jbtv.css';
import '../../css/c/c6sfqyboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><path class="x6yv7jbtv"/><path class="c6sfqyboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-circle-down" {...props}></Icon>
