<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck5xyu9ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck5xyu9ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-3-fill" {...props}></Icon>
