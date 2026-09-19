<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq59b2bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uq59b2bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:floppy-disk-filled" {...props}></Icon>
