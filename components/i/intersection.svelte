<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/a8yau0s8m.css';
import '../../css/x/x9k21mbpj.css';
import '../../css/b/baie08-3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="a8yau0s8m"/><path class="x9k21mbpj"/><rect class="baie08-3n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:intersection" {...props}></Icon>
