<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf2_240wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf2_240wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ambulatory-clinic-outline-24px" {...props}></Icon>
