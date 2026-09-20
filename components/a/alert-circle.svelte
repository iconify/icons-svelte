<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/axarcbb2r.css';
import '../../css/q/qfcjmbcnu.css';
import '../../css/h/h5_h89bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="axarcbb2r"/><path class="qfcjmbcnu"/><circle transform="matrix(1 0 0 -1 10.75 17.063)" class="h5_h89bsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:alert-circle" {...props}></Icon>
