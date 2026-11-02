<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsn74dpfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsn74dpfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-fill" {...props}></Icon>
