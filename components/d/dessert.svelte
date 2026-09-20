<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cw00x95zz.css';
import '../../css/h/hf4medc5o.css';
import '../../css/n/npzbi206w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cw00x95zz"/><path class="hf4medc5o"/><circle class="npzbi206w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:dessert" {...props}></Icon>
