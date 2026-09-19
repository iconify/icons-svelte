<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t26jdnbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t26jdnbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-folder" {...props}></Icon>
