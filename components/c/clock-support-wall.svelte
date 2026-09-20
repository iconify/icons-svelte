<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plml1nb5a.css';
import '../../css/i/iq2ggzbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plml1nb5a"/><path class="iq2ggzbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:clock-support-wall" {...props}></Icon>
