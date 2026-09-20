<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wjd95_bar.css';
import '../../css/e/egctnk0pt.css';
import '../../css/g/gf5qrfb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wjd95_bar"/><path class="egctnk0pt"/><path class="gf5qrfb2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cd-rom-disc-broken" {...props}></Icon>
