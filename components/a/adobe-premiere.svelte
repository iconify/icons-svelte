<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oap-5zu8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oap-5zu8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-premiere" {...props}></Icon>
