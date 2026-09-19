<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p22wnqbnw.css';
import '../../css/f/f1nl8yjrl.css';
import '../../css/q/q9fzk183f.css';
import '../../css/g/g9ouegxjn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSpd8pdZy"><g class="ufeehvblu"><path class="p22wnqbnw"/><path class="f1nl8yjrl"/><path class="q9fzk183f"/><path class="g9ouegxjn"/></g></mask></defs><path mask="url(#SVGSpd8pdZy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bank-card" {...props}></Icon>
