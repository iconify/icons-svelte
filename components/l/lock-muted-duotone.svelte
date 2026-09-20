<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1dviszv.css';
import '../../css/h/hiqsv9b4b.css';
import '../../css/o/ob8mo8phv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="hiqsv9b4b"/><path class="ob8mo8phv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lock-muted-duotone" {...props}></Icon>
