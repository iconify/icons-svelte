<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr3ix3wqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gr3ix3wqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:rocket-on-launch-pad" {...props}></Icon>
