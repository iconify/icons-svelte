<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/z/zdhb83szs.css';
import '../../css/r/rpsd5vp5o.css';
import '../../css/r/rsvuxndka.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKpq6fc5u"><g class="ufeehvblu"><path class="zdhb83szs"/><path class="rpsd5vp5o"/><path class="rsvuxndka"/></g></mask></defs><path mask="url(#SVGKpq6fc5u)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:local" {...props}></Icon>
