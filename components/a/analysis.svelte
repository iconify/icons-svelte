<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/n/nyc9q5jiz.css';
import '../../css/m/m_awi4b7p.css';
import '../../css/c/cyc_zi05z.css';
import '../../css/d/dimzdedth.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGSuIweNy"><g class="s9cl3zbei"><path class="nyc9q5jiz"/><path class="m_awi4b7p"/><path class="cyc_zi05z"/><path class="dimzdedth"/></g></mask></defs><path mask="url(#SVGGSuIweNy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:analysis" {...props}></Icon>
