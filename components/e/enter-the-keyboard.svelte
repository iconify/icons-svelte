<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/spcy3joli.css';
import '../../css/f/fbt_i58au.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvYKyweds"><g class="ufeehvblu"><path class="spcy3joli"/><path class="fbt_i58au"/></g></mask></defs><path mask="url(#SVGvYKyweds)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:enter-the-keyboard" {...props}></Icon>
