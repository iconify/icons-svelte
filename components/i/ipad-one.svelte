<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/af1ozmbkx.css';
import '../../css/n/n6g8ofb5v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkTn81dxT"><g class="s9cl3zbei"><rect class="af1ozmbkx"/><path class="n6g8ofb5v"/></g></mask></defs><path mask="url(#SVGkTn81dxT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ipad-one" {...props}></Icon>
