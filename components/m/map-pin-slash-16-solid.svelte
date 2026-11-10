<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9vlsyb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f9vlsyb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:map-pin-slash-16-solid" {...props}></Icon>
