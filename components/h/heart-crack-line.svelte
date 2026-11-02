<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp0427blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp0427blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-crack-line" {...props}></Icon>
