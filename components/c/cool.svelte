<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgepj_2fe.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXyBFNeJE"><path class="jgepj_2fe"/></mask></defs><path mask="url(#SVGXyBFNeJE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:cool" {...props}></Icon>
