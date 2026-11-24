<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ca_zb6s.css';
import '../../css/j/jp04aka3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ca_zb6s"/><path clip-rule="evenodd" class="jp04aka3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:donut-filled" {...props}></Icon>
