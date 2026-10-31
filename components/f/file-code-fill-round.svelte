<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbilo7g8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbilo7g8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-code-fill-round" {...props}></Icon>
