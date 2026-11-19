<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vme8u3boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vme8u3boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bazarr" {...props}></Icon>
