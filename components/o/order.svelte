<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/m/ma89ezbjd.css';
import '../../css/o/o90zhsb-g.css';
import '../../css/y/ybo_y_3hp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBCyq8bMu"><g class="ufeehvblu"><path class="ma89ezbjd"/><path class="o90zhsb-g"/><path class="ybo_y_3hp"/></g></mask></defs><path mask="url(#SVGBCyq8bMu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:order" {...props}></Icon>
