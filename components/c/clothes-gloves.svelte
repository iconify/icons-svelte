<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d48krva-u.css';
import '../../css/n/nu3w2abno.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkYqmLdhu"><g class="ft5dv1b6b"><path class="d48krva-u"/><path class="nu3w2abno"/></g></mask></defs><path mask="url(#SVGkYqmLdhu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:clothes-gloves" {...props}></Icon>
