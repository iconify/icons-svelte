<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/a_ete1bey.css';
import '../../css/o/o6o_kgbrk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOMDJUcJH"><g class="aql7dnt-u"><circle class="a_ete1bey"/><path class="o6o_kgbrk"/></g></mask></defs><path mask="url(#SVGOMDJUcJH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:handle-z" {...props}></Icon>
