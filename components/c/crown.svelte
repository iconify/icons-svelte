<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uq9jx2m6e.css';
import '../../css/d/dfaqi5b4x.css';
import '../../css/n/nvxia9buc.css';
import '../../css/u/uy2i3ccvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uq9jx2m6e"/><circle class="dfaqi5b4x"/><circle class="nvxia9buc"/><circle class="uy2i3ccvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:crown" {...props}></Icon>
