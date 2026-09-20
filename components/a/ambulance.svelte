<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nu43cebmy.css';
import '../../css/b/bf9hqaclw.css';
import '../../css/e/ec_xsy4gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nu43cebmy"/><circle class="bf9hqaclw"/><circle class="ec_xsy4gs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ambulance" {...props}></Icon>
