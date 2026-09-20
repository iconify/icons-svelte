<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5d-bc1s.css';
import '../../css/g/g9od2_b1c.css';
import '../../css/g/gexzjokqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nx5d-bc1s"><path clip-rule="evenodd" class="g9od2_b1c"/><path class="gexzjokqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openwebui" {...props}></Icon>
