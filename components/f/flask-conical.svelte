<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii0_g0bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii0_g0bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flask-conical" {...props}></Icon>
