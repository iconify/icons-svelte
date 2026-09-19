<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h85pweb1l.css';
import '../../css/z/zqpa_ob9q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIIaB77rg"><g class="v3_i3wktz"><path class="h85pweb1l"/><path class="zqpa_ob9q"/></g></mask></defs><path mask="url(#SVGIIaB77rg)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:folder-minus" {...props}></Icon>
