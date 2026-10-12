<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksderlvfw.css';
import '../../css/a/a08-prbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksderlvfw"/><path clip-rule="evenodd" class="a08-prbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banknote-arrow-down-filled" {...props}></Icon>
