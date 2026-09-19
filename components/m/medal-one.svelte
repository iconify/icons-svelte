<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/t45w3cbwe.css';
import '../../css/f/fpx-00njb.css';
import '../../css/p/ps_jx5b8q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG06LOWdxz"><g class="s9cl3zbei"><path class="t45w3cbwe"/><circle class="fpx-00njb"/><circle class="ps_jx5b8q"/></g></mask></defs><path mask="url(#SVG06LOWdxz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:medal-one" {...props}></Icon>
