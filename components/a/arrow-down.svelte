<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/patrfv0we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="patrfv0we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:arrow-down" {...props}></Icon>
