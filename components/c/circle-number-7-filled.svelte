<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcuuxbb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuuxbb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-number-7-filled" {...props}></Icon>
