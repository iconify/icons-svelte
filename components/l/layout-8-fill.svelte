<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp-narbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp-narbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-8-fill" {...props}></Icon>
