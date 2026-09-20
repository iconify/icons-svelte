<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al9_oyb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al9_oyb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-warning-fill" {...props}></Icon>
