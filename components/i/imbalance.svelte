<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/d08qanr9p.css';
import '../../css/g/gl1hokdww.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaFxh4cRS"><g class="aql7dnt-u"><path class="d08qanr9p"/><path clip-rule="evenodd" class="gl1hokdww"/></g></mask></defs><path mask="url(#SVGaFxh4cRS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:imbalance" {...props}></Icon>
