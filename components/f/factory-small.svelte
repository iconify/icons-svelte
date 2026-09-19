<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5hyoq_vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v5hyoq_vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:factory-small" {...props}></Icon>
