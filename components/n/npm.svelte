<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/han1l8bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="han1l8bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:npm" {...props}></Icon>
