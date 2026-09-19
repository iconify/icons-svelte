<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud_ovfl8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ud_ovfl8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:elevator" {...props}></Icon>
