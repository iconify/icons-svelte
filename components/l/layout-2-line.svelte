<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w52t0fnlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w52t0fnlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-2-line" {...props}></Icon>
