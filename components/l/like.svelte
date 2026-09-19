<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc2lzsb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc2lzsb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:like" {...props}></Icon>
