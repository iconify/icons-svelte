<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mqm32dw3h.css';
import '../../css/s/s97a71b-k.css';
import '../../css/q/qp80nqbjd.css';
import '../../css/l/l2v6oqb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mqm32dw3h"/><path class="s97a71b-k"/><path class="qp80nqbjd"/><path class="l2v6oqb2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plate-bold-duotone" {...props}></Icon>
