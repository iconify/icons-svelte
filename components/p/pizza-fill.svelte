<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdnqrccna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdnqrccna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pizza-fill" {...props}></Icon>
