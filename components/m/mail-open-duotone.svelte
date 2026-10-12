<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t-i69rhzg.css';
import '../../css/v/vo206n5fa.css';
import '../../css/z/z7o02f_5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t-i69rhzg"/><path class="vo206n5fa"/><path class="z7o02f_5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-open-duotone" {...props}></Icon>
