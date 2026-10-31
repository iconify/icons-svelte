<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgywo8b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgywo8b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-code-gloss" {...props}></Icon>
