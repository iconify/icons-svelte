<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdvqu6b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gdvqu6b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:eye" {...props}></Icon>
