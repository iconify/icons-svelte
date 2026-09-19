<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h911x3vnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h911x3vnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:diagonal-cross" {...props}></Icon>
