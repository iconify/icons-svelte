<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx3mzzwyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rx3mzzwyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-with-ok-gesture" {...props}></Icon>
