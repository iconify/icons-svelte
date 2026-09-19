<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-8-qhbnp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn3H0fbpu"><path clip-rule="evenodd" class="n-8-qhbnp"/></mask></defs><path mask="url(#SVGn3H0fbpu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:right-angle" {...props}></Icon>
