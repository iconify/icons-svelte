<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lesw936ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lesw936ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cursing-face" {...props}></Icon>
