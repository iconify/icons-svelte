<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl8_zgbvz.css';
import '../../css/o/o5nyr_biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pl8_zgbvz"/><path class="o5nyr_biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hand-platter-filled" {...props}></Icon>
