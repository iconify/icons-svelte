<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek9xd-8cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ek9xd-8cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hammer-filled" {...props}></Icon>
