<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m12-_eblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m12-_eblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-exclamation-point" {...props}></Icon>
