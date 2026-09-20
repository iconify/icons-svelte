<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_dc_jjcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_dc_jjcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fogo" {...props}></Icon>
