<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h6p28il0s.css';
import '../../css/f/f4res6apk.css';
import '../../css/i/i9m88b5ko.css';
import '../../css/x/xyvq88qxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h6p28il0s"/><path class="f4res6apk"/><path class="i9m88b5ko"/><path class="xyvq88qxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-radar" {...props}></Icon>
