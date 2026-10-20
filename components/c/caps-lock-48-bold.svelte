<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5v9g9qtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m5v9g9qtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caps-lock-48-bold" {...props}></Icon>
