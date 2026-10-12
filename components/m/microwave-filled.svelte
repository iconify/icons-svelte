<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhjm4i6en.css';
import '../../css/m/mol_khq9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhjm4i6en"/><path clip-rule="evenodd" class="mol_khq9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:microwave-filled" {...props}></Icon>
