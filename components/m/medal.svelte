<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/de2zti8vg.css';
import '../../css/x/xu1251juh.css';
import '../../css/h/hieh39bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="de2zti8vg"/><circle class="xu1251juh"/><path class="hieh39bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:medal" {...props}></Icon>
