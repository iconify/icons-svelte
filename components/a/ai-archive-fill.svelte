<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ges_wsysv.css';
import '../../css/f/fcjlr1v_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ges_wsysv"/><path clip-rule="evenodd" class="fcjlr1v_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-archive-fill" {...props}></Icon>
