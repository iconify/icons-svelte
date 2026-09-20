<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqmqxhpqk.css';
import '../../css/n/n5t4ppego.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqmqxhpqk"/><path class="n5t4ppego"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bus-1" {...props}></Icon>
