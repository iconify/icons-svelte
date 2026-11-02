<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9ywx-8pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ywx-8pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:engine-line" {...props}></Icon>
