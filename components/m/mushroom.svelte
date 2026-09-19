<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5b9rwc-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l5b9rwc-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mushroom" {...props}></Icon>
