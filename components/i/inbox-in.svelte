<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/ct1r7w1hv.css';
import '../../css/l/lmhlr-bsl.css';
import '../../css/x/xu7x7kbnb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6S9q1S5Z"><g class="v3_i3wktz"><path class="ct1r7w1hv"/><path class="lmhlr-bsl"/><path class="xu7x7kbnb"/></g></mask></defs><path mask="url(#SVG6S9q1S5Z)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:inbox-in" {...props}></Icon>
