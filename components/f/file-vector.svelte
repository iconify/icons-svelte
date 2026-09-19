<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az_a87o8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="az_a87o8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-vector" {...props}></Icon>
