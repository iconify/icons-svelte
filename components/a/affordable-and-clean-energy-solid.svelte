<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lombof_ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lombof_ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:affordable-and-clean-energy-solid" {...props}></Icon>
