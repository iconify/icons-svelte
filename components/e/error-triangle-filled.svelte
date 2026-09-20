<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8e9dnbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8e9dnbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:error-triangle-filled" {...props}></Icon>
