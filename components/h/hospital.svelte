<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tb-dkyakg.css';
import '../../css/b/bs7qipb-w.css';
import '../../css/i/iosag-ytp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tb-dkyakg"/><path class="bs7qipb-w"/><path class="iosag-ytp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:hospital" {...props}></Icon>
