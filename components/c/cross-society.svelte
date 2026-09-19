<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8qun1bmd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPM99xcmU"><path class="y8qun1bmd"/></mask></defs><path mask="url(#SVGPM99xcmU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:cross-society" {...props}></Icon>
