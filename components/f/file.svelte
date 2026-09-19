<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx_auznvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_auznvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:file" {...props}></Icon>
