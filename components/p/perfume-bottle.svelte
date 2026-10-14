<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xn184--be.css';
import '../../css/l/lyok8tb9e.css';
import '../../css/o/os09ombsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xn184--be"/><circle class="lyok8tb9e"/><rect class="os09ombsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:perfume-bottle" {...props}></Icon>
