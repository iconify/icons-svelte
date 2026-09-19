<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/llper-sbd.css';
import '../../css/r/r6i16ds0i.css';
import '../../css/o/o8ul-lbzg.css';
import '../../css/f/fch3yqjjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="llper-sbd"/><circle class="r6i16ds0i"/><path class="o8ul-lbzg"/><path class="fch3yqjjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:expressionless-face-duotone" {...props}></Icon>
