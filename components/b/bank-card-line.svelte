<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqviyccnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqviyccnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bank-card-line" {...props}></Icon>
