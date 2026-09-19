<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjpmnbata.css';
import '../../css/k/ku47_bc8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjpmnbata"/><path class="ku47_bc8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-exclamation" {...props}></Icon>
