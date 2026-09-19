<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2fb11kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ve2fb11kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-arrow-circled-filled" {...props}></Icon>
