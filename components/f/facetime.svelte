<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/o/ot_tbvbcc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjQPqWdiy"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="ot_tbvbcc"/></g></mask></defs><path mask="url(#SVGjQPqWdiy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:facetime" {...props}></Icon>
