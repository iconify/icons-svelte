<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjwtpxbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjwtpxbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-line-smooth" {...props}></Icon>
