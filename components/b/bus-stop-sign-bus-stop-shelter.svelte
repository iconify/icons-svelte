<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3p8q1brp.css';
import '../../css/q/qv0m_7bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r3p8q1brp"/><path class="qv0m_7bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bus-stop-sign-bus-stop-shelter" {...props}></Icon>
