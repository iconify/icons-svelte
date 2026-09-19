<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gnens_cuk.css';
import '../../css/n/n0tohdbyd.css';
import '../../css/f/fz171i7ps.css';
import '../../css/z/zv7vgacil.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaJOJcZjJ"><g class="ufeehvblu"><path class="gnens_cuk"/><path class="n0tohdbyd"/><path class="fz171i7ps"/><path class="zv7vgacil"/></g></mask></defs><path mask="url(#SVGaJOJcZjJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:broadcast-radio" {...props}></Icon>
