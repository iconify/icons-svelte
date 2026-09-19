<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3h98r3ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t3h98r3ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-frac-small-filled" {...props}></Icon>
