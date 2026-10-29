<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo488-cjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo488-cjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-desk" {...props}></Icon>
