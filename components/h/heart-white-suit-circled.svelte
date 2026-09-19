<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bntco1b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bntco1b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-white-suit-circled" {...props}></Icon>
