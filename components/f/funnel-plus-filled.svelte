<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx7s2abfj.css';
import '../../css/e/exoou0b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx7s2abfj"/><path class="exoou0b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:funnel-plus-filled" {...props}></Icon>
