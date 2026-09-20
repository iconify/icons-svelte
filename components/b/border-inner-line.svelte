<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi345vbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi345vbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-inner-line" {...props}></Icon>
