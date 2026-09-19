<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orbc7kbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orbc7kbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:palette-filled" {...props}></Icon>
