<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z708rvtlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z708rvtlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dash0" {...props}></Icon>
