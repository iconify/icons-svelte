<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6bk4pu6o.css';
import '../../css/j/j7r8t5bzq.css';
import '../../css/g/gu8gak4xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6bk4pu6o"/><rect class="j7r8t5bzq"/><rect class="gu8gak4xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:between-horizontal-end-filled" {...props}></Icon>
