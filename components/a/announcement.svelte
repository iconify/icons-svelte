<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jiqs0bwjn.css';
import '../../css/t/tnva8r8up.css';
import '../../css/i/ic972l8rf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbrrVVdvZ"><g class="ufeehvblu"><rect class="jiqs0bwjn"/><path class="tnva8r8up"/><path class="ic972l8rf"/></g></mask></defs><path mask="url(#SVGbrrVVdvZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:announcement" {...props}></Icon>
