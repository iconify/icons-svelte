<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/s2aj9_bcg.css';
import '../../css/c/ca4p52b-o.css';
import '../../css/k/ko2bb1nmy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7G5Vme8g"><g class="ufeehvblu"><path class="s2aj9_bcg"/><path class="ca4p52b-o"/><path class="ko2bb1nmy"/></g></mask></defs><path mask="url(#SVG7G5Vme8g)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:flashlight" {...props}></Icon>
