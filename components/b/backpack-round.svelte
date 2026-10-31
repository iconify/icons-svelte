<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcxeust6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcxeust6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:backpack-round" {...props}></Icon>
