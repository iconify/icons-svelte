<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_b8l4bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_b8l4bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-clock-x-solid" {...props}></Icon>
