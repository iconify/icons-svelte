<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn6m6h7bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nn6m6h7bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-fwid-small-filled" {...props}></Icon>
