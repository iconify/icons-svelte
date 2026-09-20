<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onocauoox.css';
import '../../css/l/lpwvf4b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onocauoox"/><path class="lpwvf4b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fingerprint-fill" {...props}></Icon>
