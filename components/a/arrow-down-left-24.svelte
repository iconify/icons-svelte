<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg3c0pb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg3c0pb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-down-left-24" {...props}></Icon>
