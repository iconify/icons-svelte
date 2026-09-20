<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zc50e7bly.css';
import '../../css/b/bri85kbqp.css';
import '../../css/l/l-4z_-b_x.css';
import '../../css/b/b-v3dtbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zc50e7bly"/><circle class="bri85kbqp"/><path class="l-4z_-b_x"/><circle class="b-v3dtbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:pram" {...props}></Icon>
