<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/iavqdjdgi.css';
import '../../css/n/npiz6qlvn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGblMKScBJ"><g class="aql7dnt-u"><path clip-rule="evenodd" class="iavqdjdgi"/><path class="npiz6qlvn"/></g></mask></defs><path mask="url(#SVGblMKScBJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hanger" {...props}></Icon>
