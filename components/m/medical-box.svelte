<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/ky4zetb4b.css';
import '../../css/o/oc2jhta3x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhjkrxcUE"><g class="s9cl3zbei"><path class="ky4zetb4b"/><path class="oc2jhta3x"/></g></mask></defs><path mask="url(#SVGhjkrxcUE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:medical-box" {...props}></Icon>
