<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awmkfjszx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="awmkfjszx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:circled-information-source" {...props}></Icon>
