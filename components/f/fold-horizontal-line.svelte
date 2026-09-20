<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp1jkewkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp1jkewkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-horizontal-line" {...props}></Icon>
