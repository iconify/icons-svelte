<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuobntlfo.css';
import '../../css/r/r8h9qdcac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuobntlfo"/><path clip-rule="evenodd" class="r8h9qdcac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-up-minimlistic-outline" {...props}></Icon>
