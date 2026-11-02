<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqau3ebwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqau3ebwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-line" {...props}></Icon>
