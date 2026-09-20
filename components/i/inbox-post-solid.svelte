<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3cao43jn.css';
import '../../css/f/f13cyk52i.css';
import '../../css/s/smok2x2qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u3cao43jn"/><path clip-rule="evenodd" class="f13cyk52i"/><path class="smok2x2qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:inbox-post-solid" {...props}></Icon>
