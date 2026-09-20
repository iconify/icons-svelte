<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnoy0zbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnoy0zbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linuxserver" {...props}></Icon>
