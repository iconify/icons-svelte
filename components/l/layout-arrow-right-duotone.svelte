<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bbp5-zmse.css';
import '../../css/f/fpv1krh2n.css';
import '../../css/d/d04rami8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bbp5-zmse"/><path class="fpv1krh2n"/><path class="d04rami8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-arrow-right-duotone" {...props}></Icon>
