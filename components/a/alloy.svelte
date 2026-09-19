<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0wxxkbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0wxxkbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:alloy" {...props}></Icon>
