<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgga7abld.css';
import '../../css/h/h8sbx2b5d.css';
import '../../css/n/nzovm6bgd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGueEmudQp"><g class="cgga7abld"><path class="h8sbx2b5d"/><path class="nzovm6bgd"/></g></mask></defs><path mask="url(#SVGueEmudQp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:gymnastics" {...props}></Icon>
