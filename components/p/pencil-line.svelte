<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssnjoqlqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssnjoqlqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-line" {...props}></Icon>
