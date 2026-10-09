<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enr033rrc.css';
import '../../css/j/jvpc1i4ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="enr033rrc"/><path class="jvpc1i4ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-horizontal-20-bold" {...props}></Icon>
