<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp4rjm96f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="rp4rjm96f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:align-left" {...props}></Icon>
