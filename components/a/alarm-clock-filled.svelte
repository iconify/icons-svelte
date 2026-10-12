<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o16g-nult.css';
import '../../css/d/du-r1xbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o16g-nult"/><path class="du-r1xbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:alarm-clock-filled" {...props}></Icon>
