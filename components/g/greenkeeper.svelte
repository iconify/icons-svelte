<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqv5a7bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqv5a7bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:greenkeeper" {...props}></Icon>
