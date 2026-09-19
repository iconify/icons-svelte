<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay2czcqmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ay2czcqmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:monkey-face" {...props}></Icon>
