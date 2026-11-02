<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k08lv-bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k08lv-bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rose-line" {...props}></Icon>
