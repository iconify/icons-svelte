<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ailzqs9ba.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/clsa-9bqs.css';
import '../../css/l/lcvnx1bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<defs><path id="iconify-CgctXtuA" class="ailzqs9ba"/></defs><g class="ft5dv1b6b"><path class="clsa-9bqs"/><use href="#iconify-CgctXtuA"/><path clip-rule="evenodd" class="lcvnx1bva"/><use href="#iconify-CgctXtuA"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:clipboard" {...props}></Icon>
