<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7mumeb-d.css';
import '../../css/u/uri7qm5ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m7mumeb-d"/><path class="uri7qm5ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-4-fill" {...props}></Icon>
