<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/a/a8rml3bpr.css';
import '../../css/a/am3i6jbjw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGY0EtEeTz"><g class="ufeehvblu"><path class="a8rml3bpr"/><path class="am3i6jbjw"/></g></mask></defs><path mask="url(#SVGY0EtEeTz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ghost" {...props}></Icon>
