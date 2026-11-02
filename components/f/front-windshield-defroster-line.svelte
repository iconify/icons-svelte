<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_p2-wb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_p2-wb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:front-windshield-defroster-line" {...props}></Icon>
