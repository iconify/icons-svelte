<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4-njpbvj.css';
import '../../css/i/ity428tdo.css';
import '../../css/p/pembsco1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4-njpbvj"/><path class="ity428tdo"/><path class="pembsco1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radio-tower-filled" {...props}></Icon>
