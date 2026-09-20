<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip0-r-tkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip0-r-tkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:file-alert" {...props}></Icon>
