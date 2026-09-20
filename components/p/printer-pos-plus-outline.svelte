<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq_i8y-mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq_i8y-mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-plus-outline" {...props}></Icon>
