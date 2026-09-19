<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtl2wew-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtl2wew-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cobol" {...props}></Icon>
