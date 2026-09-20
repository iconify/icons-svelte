<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd6en3etl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd6en3etl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:components-solid" {...props}></Icon>
