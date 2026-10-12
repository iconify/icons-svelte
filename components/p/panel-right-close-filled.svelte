<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq9hu5f5m.css';
import '../../css/n/ndqjaugsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aq9hu5f5m"/><path class="ndqjaugsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-right-close-filled" {...props}></Icon>
