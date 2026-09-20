<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjwc3fslb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjwc3fslb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftsqlserver" {...props}></Icon>
