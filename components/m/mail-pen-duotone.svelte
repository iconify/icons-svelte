<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uk8te3bak.css';
import '../../css/g/gnc4ceb8u.css';
import '../../css/v/ve33t5vys.css';
import '../../css/s/sigei6ulc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uk8te3bak"/><path class="gnc4ceb8u"/><path class="ve33t5vys"/><path class="sigei6ulc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-pen-duotone" {...props}></Icon>
