<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/q6e3cs9co.css';
import '../../css/g/gwal899za.css';
import '../../css/s/si9kwcchz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6e3cs9co"/><path class="gwal899za"/><path class="si9kwcchz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lamp-2" {...props}></Icon>
