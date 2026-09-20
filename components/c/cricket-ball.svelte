<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qu0emtbbx.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/e/e8abpcfvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qu0emtbbx"/><circle class="shu3xdl9q"/><path class="e8abpcfvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cricket-ball" {...props}></Icon>
