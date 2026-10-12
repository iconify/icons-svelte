<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ca_zb6s.css';
import '../../css/g/gp21txb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ca_zb6s"/><path clip-rule="evenodd" class="gp21txb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bolt-filled" {...props}></Icon>
