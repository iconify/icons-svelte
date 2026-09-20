<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k072b1bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k072b1bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:order-numeric-ascending" {...props}></Icon>
