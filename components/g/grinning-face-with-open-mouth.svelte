<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/k/kemfc8bkc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsObFcebz"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="kemfc8bkc"/></g></mask></defs><path mask="url(#SVGsObFcebz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:grinning-face-with-open-mouth" {...props}></Icon>
