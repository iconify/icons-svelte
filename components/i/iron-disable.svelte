<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qkde5pb7p.css';
import '../../css/g/g09b36oos.css';
import '../../css/z/z1bj45_8a.css';
import '../../css/i/igx57ccmj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXarHtcLD"><g class="aql7dnt-u"><path class="qkde5pb7p"/><path class="g09b36oos"/><circle class="z1bj45_8a"/><path class="igx57ccmj"/></g></mask></defs><path mask="url(#SVGXarHtcLD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:iron-disable" {...props}></Icon>
