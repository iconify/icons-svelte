<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uu_7a4y3p.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/q/qsu9n_98r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uu_7a4y3p"/><circle class="zv6cqnbnp"/><path class="qsu9n_98r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:map-pin-minus" {...props}></Icon>
