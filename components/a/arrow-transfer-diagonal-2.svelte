<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s03g3-7yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s03g3-7yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-transfer-diagonal-2" {...props}></Icon>
