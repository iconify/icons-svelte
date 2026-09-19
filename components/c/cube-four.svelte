<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/n/n7zicvbeq.css';
import '../../css/a/aruhpbctm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuw3bhdvp"><g class="wwvp95byt"><path class="n7zicvbeq"/><path class="aruhpbctm"/></g></mask></defs><path mask="url(#SVGuw3bhdvp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:cube-four" {...props}></Icon>
