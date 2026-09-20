<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7pm8byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu7pm8byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bone-line" {...props}></Icon>
