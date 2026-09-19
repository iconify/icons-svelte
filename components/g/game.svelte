<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g4rirbcmo.css';
import '../../css/u/u3e_2wb-h.css';
import '../../css/z/z284ub4xi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGY8N6Iblf"><g class="ufeehvblu"><path class="g4rirbcmo"/><path class="u3e_2wb-h"/><path class="z284ub4xi"/></g></mask></defs><path mask="url(#SVGY8N6Iblf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:game" {...props}></Icon>
