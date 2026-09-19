<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/u9x8qellr.css';
import '../../css/i/i3yq3qbys.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbWq8PeLv"><g class="v3_i3wktz"><path class="u9x8qellr"/><path class="i3yq3qbys"/></g></mask></defs><path mask="url(#SVGbWq8PeLv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:resistor" {...props}></Icon>
