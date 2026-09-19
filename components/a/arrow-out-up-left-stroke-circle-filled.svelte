<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv8it5a_b.css';
import '../../css/g/g82lygpra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv8it5a_b"/><path class="g82lygpra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-left-stroke-circle-filled" {...props}></Icon>
