<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/ve33t5vys.css';
import '../../css/q/q050sk4js.css';
import '../../css/s/sigei6ulc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ve33t5vys"/><path class="q050sk4js"/><path class="sigei6ulc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-duotone" {...props}></Icon>
