<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nwindnbjv.css';
import '../../css/t/tajxpcbfy.css';
import '../../css/b/bdaj99b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nwindnbjv"/><path class="tajxpcbfy"/><path class="bdaj99b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:mortarboard-alt" {...props}></Icon>
