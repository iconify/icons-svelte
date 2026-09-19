<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paq201bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="paq201bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:checkmark-circled-small-filled" {...props}></Icon>
