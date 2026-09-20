<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpswnhbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpswnhbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-4-fill" {...props}></Icon>
