<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tugnq-b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tugnq-b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-circle-for-record-filled" {...props}></Icon>
