<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbsdqxnvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbsdqxnvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:body-line" {...props}></Icon>
