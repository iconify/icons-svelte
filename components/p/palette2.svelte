<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v52pddcbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v52pddcbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:palette2" {...props}></Icon>
