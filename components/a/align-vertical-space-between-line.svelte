<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kugertb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kugertb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-space-between-line" {...props}></Icon>
