<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghylczb-n.css';
import '../../css/s/svi8x9byo.css';
import '../../css/d/dj90s9bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghylczb-n"/><path class="svi8x9byo"/><path clip-rule="evenodd" class="dj90s9bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-forbid-fill" {...props}></Icon>
