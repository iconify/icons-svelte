<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thw5170-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thw5170-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:code" {...props}></Icon>
