<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rccdzuh8z.css';
import '../../css/d/du-r1xbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rccdzuh8z"/><path class="du-r1xbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:alarm-clock-minus-filled" {...props}></Icon>
