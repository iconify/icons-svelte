<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h32jkxbzn.css';
import '../../css/k/kg0gpsori.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h32jkxbzn"/><path class="kg0gpsori"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:archive-add-2" {...props}></Icon>
