<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/i5hd2ab8w.css';
import '../../css/a/a82fk-r5o.css';
import '../../css/a/a3tlaubzd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPfpbUL5T"><g class="aql7dnt-u"><path class="i5hd2ab8w"/><path class="a82fk-r5o"/><path class="a3tlaubzd"/></g></mask></defs><path mask="url(#SVGPfpbUL5T)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:keyline" {...props}></Icon>
