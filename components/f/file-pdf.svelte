<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/ab1-j-jdh.css';
import '../../css/m/mlk1wnbwb.css';
import '../../css/v/vz5pg1b6t.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOhThJbBT"><g class="s9cl3zbei"><path class="ab1-j-jdh"/><path clip-rule="evenodd" class="mlk1wnbwb"/><path class="vz5pg1b6t"/></g></mask></defs><path mask="url(#SVGOhThJbBT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:file-pdf" {...props}></Icon>
