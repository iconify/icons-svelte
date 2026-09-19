<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/s/stexj9blz.css';
import '../../css/r/r6xesbc5x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdS2opdAL"><g class="s9cl3zbei"><rect class="stexj9blz"/><path class="r6xesbc5x"/></g></mask></defs><path mask="url(#SVGdS2opdAL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:iphone" {...props}></Icon>
