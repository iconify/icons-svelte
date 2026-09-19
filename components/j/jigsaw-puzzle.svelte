<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcz48-bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lcz48-bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:jigsaw-puzzle" {...props}></Icon>
