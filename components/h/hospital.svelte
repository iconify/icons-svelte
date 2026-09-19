<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/o3z6e4byv.css';
import '../../css/m/mo-ovh0xf.css';
import '../../css/w/wk9hsib2c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsY4msekX"><g class="s9cl3zbei"><path class="o3z6e4byv"/><path class="mo-ovh0xf"/><path class="wk9hsib2c"/></g></mask></defs><path mask="url(#SVGsY4msekX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hospital" {...props}></Icon>
