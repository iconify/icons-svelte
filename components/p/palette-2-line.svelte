<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggdj-rbkr.css';
import '../../css/d/d4aj_070k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggdj-rbkr"/><circle class="d4aj_070k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-2-line" {...props}></Icon>
