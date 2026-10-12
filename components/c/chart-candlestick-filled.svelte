<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sozdzcb0a.css';
import '../../css/o/om5h7lb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path class="om5h7lb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-candlestick-filled" {...props}></Icon>
