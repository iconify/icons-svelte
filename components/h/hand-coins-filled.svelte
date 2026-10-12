<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac0nmw1ig.css';
import '../../css/a/alo-6-b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ac0nmw1ig"/><path class="alo-6-b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hand-coins-filled" {...props}></Icon>
