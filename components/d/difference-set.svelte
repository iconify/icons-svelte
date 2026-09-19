<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zagbpsbzf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcMa9891I"><path class="zagbpsbzf"/></mask></defs><path mask="url(#SVGcMa9891I)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:difference-set" {...props}></Icon>
