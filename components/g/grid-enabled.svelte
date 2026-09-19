<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz-65_bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lz-65_bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:grid-enabled" {...props}></Icon>
