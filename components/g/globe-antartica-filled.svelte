<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmsleubgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmsleubgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-antartica-filled" {...props}></Icon>
