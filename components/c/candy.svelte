<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/dvcapvbcu.css';
import '../../css/m/met-ksu1r.css';
import '../../css/p/peimmofsp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWrHFzcHE"><g class="s9cl3zbei"><circle class="dvcapvbcu"/><path class="met-ksu1r"/><path class="peimmofsp"/></g></mask></defs><path mask="url(#SVGWrHFzcHE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:candy" {...props}></Icon>
