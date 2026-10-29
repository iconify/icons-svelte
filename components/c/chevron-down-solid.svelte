<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emkqpcc5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emkqpcc5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-down-solid" {...props}></Icon>
