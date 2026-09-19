<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fgokb7h8d.css';
import '../../css/z/zw-68k1ry.css';
import '../../css/z/z2hbabcdb.css';
import '../../css/a/al3gikwgt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYReMxexd"><g class="ufeehvblu"><path class="fgokb7h8d"/><rect class="zw-68k1ry"/><rect class="z2hbabcdb"/><path class="al3gikwgt"/></g></mask></defs><path mask="url(#SVGYReMxexd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:city-one" {...props}></Icon>
