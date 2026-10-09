<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bybnubbfi.css';
import '../../css/b/bc05qzspk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bybnubbfi"/><path class="bc05qzspk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacitor-48" {...props}></Icon>
