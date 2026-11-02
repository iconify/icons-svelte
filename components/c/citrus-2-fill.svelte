<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icgmf0-ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icgmf0-ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:citrus-2-fill" {...props}></Icon>
