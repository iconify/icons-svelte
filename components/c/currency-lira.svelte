<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icmq1lb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icmq1lb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-lira" {...props}></Icon>
