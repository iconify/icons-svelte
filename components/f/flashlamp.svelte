<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/r/rt4zo2bpe.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaVrrHcAf"><g class="s9cl3zbei"><circle class="mzszod_2j"/><path class="rt4zo2bpe"/></g></mask></defs><path mask="url(#SVGaVrrHcAf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:flashlamp" {...props}></Icon>
