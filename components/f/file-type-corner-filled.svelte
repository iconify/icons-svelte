<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b21cvhnzr.css';
import '../../css/e/eqmcswb4q.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b21cvhnzr"/><path class="eqmcswb4q"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-type-corner-filled" {...props}></Icon>
