<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/g/g1z_4obql.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXRfEhbhv"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="g1z_4obql"/></g></mask></defs><path mask="url(#SVGXRfEhbhv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:electrocardiogram" {...props}></Icon>
