<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy1w_4b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy1w_4b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-upload-corner-fill-round" {...props}></Icon>
