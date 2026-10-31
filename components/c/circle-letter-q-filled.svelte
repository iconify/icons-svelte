<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3__ojbef.css';
import '../../css/d/dwrhhxelk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3__ojbef"/><path clip-rule="evenodd" class="dwrhhxelk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-q-filled" {...props}></Icon>
