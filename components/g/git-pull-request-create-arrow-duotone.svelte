<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x-40i3b7x.css';
import '../../css/i/i4us9_bhu.css';
import '../../css/o/op6fncb7i.css';
import '../../css/j/j7cxyrbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x-40i3b7x"/><path class="i4us9_bhu"/><path class="op6fncb7i"/><path class="j7cxyrbtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-create-arrow-duotone" {...props}></Icon>
