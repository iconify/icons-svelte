<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz7exac3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz7exac3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:error-circle-filled" {...props}></Icon>
