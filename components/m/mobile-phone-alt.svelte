<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew3xsfbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ew3xsfbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mobile-phone-alt" {...props}></Icon>
