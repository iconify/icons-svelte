<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1ly0bcpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x1ly0bcpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:girl-small" {...props}></Icon>
