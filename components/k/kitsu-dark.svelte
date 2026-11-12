<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/durrixbcc.css';
import '../../css/h/hf869sb1k.css';
import '../../css/h/hibcrvbqz.css';
import '../../css/h/hina6zh8z.css';
import '../../css/m/mq_a-6b-m.css';
import '../../css/q/qz7uzdb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="durrixbcc"/><path class="hf869sb1k"/><path class="hibcrvbqz"/><path class="hina6zh8z"/><path class="mq_a-6b-m"/><path class="qz7uzdb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitsu-dark" {...props}></Icon>
