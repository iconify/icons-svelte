<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfmbfrbpt.css';
import '../../css/g/ga2dqzb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfmbfrbpt"/><path class="ga2dqzb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bread" {...props}></Icon>
