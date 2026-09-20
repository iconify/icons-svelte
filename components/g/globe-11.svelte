<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l377ax9ox.css';
import '../../css/e/elc9xubaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="l377ax9ox"/><path class="elc9xubaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:globe-11" {...props}></Icon>
