<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqkph08dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqkph08dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-6-line" {...props}></Icon>
