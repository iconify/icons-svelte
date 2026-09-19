<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bcth3ex-n.css';
import '../../css/r/r6i16ds0i.css';
import '../../css/h/hg066707f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="bcth3ex-n"/><circle class="r6i16ds0i"/><path class="hg066707f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:discover-duotone" {...props}></Icon>
