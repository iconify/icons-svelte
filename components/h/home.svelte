<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/h/hoy2h8bpa.css';
import '../../css/u/uxe07sber.css';
import '../../css/z/znbzetb7r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUEQMbVPJ"><g class="s9cl3zbei"><path class="hoy2h8bpa"/><path class="uxe07sber"/><path class="znbzetb7r"/></g></mask></defs><path mask="url(#SVGUEQMbVPJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:home" {...props}></Icon>
