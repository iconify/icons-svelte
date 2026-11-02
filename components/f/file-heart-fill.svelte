<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihhymhb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihhymhb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-heart-fill" {...props}></Icon>
