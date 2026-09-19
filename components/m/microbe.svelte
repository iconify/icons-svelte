<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrbmz5bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lrbmz5bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:microbe" {...props}></Icon>
