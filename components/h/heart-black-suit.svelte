<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7diirbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t7diirbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-black-suit" {...props}></Icon>
