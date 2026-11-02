<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o33txrb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o33txrb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-big-right-dash-line" {...props}></Icon>
