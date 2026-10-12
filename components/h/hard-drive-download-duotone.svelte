<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aly3ipb5i.css';
import '../../css/o/oly-m626v.css';
import '../../css/q/qt56rzevo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aly3ipb5i"/><path class="oly-m626v"/><path class="qt56rzevo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hard-drive-download-duotone" {...props}></Icon>
