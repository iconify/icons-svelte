<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/p/piwg5-x2u.css';
import '../../css/w/w9aixnb4p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZQc1T6is"><g class="hv130ab-t"><path class="piwg5-x2u"/><path class="w9aixnb4p"/></g></mask></defs><path mask="url(#SVGZQc1T6is)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:horizontally-centered" {...props}></Icon>
