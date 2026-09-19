<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kf9iljxev.css';
import '../../css/i/iog5bvc2b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDiIGbbnD"><g class="v3_i3wktz"><rect class="kf9iljxev"/><path class="iog5bvc2b"/></g></mask></defs><path mask="url(#SVGDiIGbbnD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:box" {...props}></Icon>
