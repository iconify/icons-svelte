<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/eggrvn9ds.css';
import '../../css/s/s13dhxbgk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSyLUNz4N"><g class="v3_i3wktz"><path class="eggrvn9ds"/><path class="s13dhxbgk"/></g></mask></defs><path mask="url(#SVGSyLUNz4N)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:circle-two-line" {...props}></Icon>
