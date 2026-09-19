<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/acxhtihbv.css';
import '../../css/t/t37nn6bko.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlsC6fdGG"><g class="s9cl3zbei"><path clip-rule="evenodd" class="acxhtihbv"/><path class="t37nn6bko"/></g></mask></defs><path mask="url(#SVGlsC6fdGG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:pills" {...props}></Icon>
