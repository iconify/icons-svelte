<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bbp5-zmse.css';
import '../../css/f/fpv1krh2n.css';
import '../../css/v/v5s1xy_2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bbp5-zmse"/><path class="fpv1krh2n"/><path class="v5s1xy_2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-arrow-down-duotone" {...props}></Icon>
