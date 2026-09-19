<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/v/v0dofs9fn.css';
import '../../css/h/hpluv7gvx.css';
import '../../css/w/wvkle8b0a.css';
import '../../css/i/i1qkqjmcg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGBoFQb9z"><g class="s9cl3zbei"><path class="v0dofs9fn"/><path class="hpluv7gvx"/><path class="wvkle8b0a"/><path class="i1qkqjmcg"/></g></mask></defs><path mask="url(#SVGGBoFQb9z)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:general-branch" {...props}></Icon>
