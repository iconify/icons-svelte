<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqmz5zbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lqmz5zbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:coconut" {...props}></Icon>
