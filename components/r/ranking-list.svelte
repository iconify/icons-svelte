<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/cyqjerbjs.css';
import '../../css/b/bztzw5bin.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnDF6vd6S"><g class="s9cl3zbei"><path class="cyqjerbjs"/><path class="bztzw5bin"/></g></mask></defs><path mask="url(#SVGnDF6vd6S)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ranking-list" {...props}></Icon>
