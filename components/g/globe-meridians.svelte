<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egyihqb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="egyihqb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:globe-meridians" {...props}></Icon>
