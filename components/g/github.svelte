<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1y-gc4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gr1y-gc4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:github" {...props}></Icon>
