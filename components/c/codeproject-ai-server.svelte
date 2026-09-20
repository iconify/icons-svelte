<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh0rf-b9f.css';
import '../../css/b/b54wsupbd.css';
import '../../css/t/trippqbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kh0rf-b9f"/><path class="b54wsupbd"/><path class="trippqbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:codeproject-ai-server" {...props}></Icon>
