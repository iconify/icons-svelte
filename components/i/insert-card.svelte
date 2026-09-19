<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nvjxntb_m.css';
import '../../css/f/fopngibfa.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzW6Fdctb"><g class="v3_i3wktz"><path class="nvjxntb_m"/><path class="fopngibfa"/></g></mask></defs><path mask="url(#SVGzW6Fdctb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:insert-card" {...props}></Icon>
