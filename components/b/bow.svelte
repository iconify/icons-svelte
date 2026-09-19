<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/bmx2kpbdt.css';
import '../../css/o/o3op-rbzi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGm5JjudRj"><g class="aql7dnt-u"><path class="bmx2kpbdt"/><path class="o3op-rbzi"/></g></mask></defs><path mask="url(#SVGm5JjudRj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bow" {...props}></Icon>
