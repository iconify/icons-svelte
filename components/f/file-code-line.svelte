<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmkebn1_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmkebn1_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-code-line" {...props}></Icon>
