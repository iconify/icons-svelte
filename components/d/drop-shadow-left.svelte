<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/d/dx3-s3bgy.css';
import '../../css/p/pvol4__sc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8Rmg3d6V"><g class="hv130ab-t"><path clip-rule="evenodd" class="dx3-s3bgy"/><path class="pvol4__sc"/></g></mask></defs><path mask="url(#SVG8Rmg3d6V)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:drop-shadow-left" {...props}></Icon>
