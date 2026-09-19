<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adexpl72i.css';
import '../../css/o/obtq3bw8r.css';
import '../../css/t/th81deifi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGByKIDebf"><g class="adexpl72i"><path clip-rule="evenodd" class="obtq3bw8r"/><path class="th81deifi"/></g></mask></defs><path mask="url(#SVGByKIDebf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:circle-four" {...props}></Icon>
