<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5hqpcc7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5hqpcc7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:jaguar" {...props}></Icon>
