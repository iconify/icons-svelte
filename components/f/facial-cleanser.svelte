<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/q9_e0ab3k.css';
import '../../css/e/eiyu3qb0h.css';
import '../../css/e/ezkgjkbvi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTshhGczL"><g class="s9cl3zbei"><path class="q9_e0ab3k"/><path class="eiyu3qb0h"/><path class="ezkgjkbvi"/></g></mask></defs><path mask="url(#SVGTshhGczL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:facial-cleanser" {...props}></Icon>
