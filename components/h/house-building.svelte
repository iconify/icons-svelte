<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig1xo-bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ig1xo-bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:house-building" {...props}></Icon>
