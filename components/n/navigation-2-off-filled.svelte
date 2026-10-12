<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gscxrkdyg.css';
import '../../css/d/du48p_lje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gscxrkdyg"/><path clip-rule="evenodd" class="du48p_lje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:navigation-2-off-filled" {...props}></Icon>
