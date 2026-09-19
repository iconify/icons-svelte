<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/d/d21eg8_0m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIkitMbSJ"><g class="s9cl3zbei"><circle class="mzszod_2j"/><path class="d21eg8_0m"/></g></mask></defs><path mask="url(#SVGIkitMbSJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:add-text-two" {...props}></Icon>
