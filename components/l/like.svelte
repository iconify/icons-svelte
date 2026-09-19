<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxxz6v6tu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtMBvKcON"><path class="hxxz6v6tu"/></mask></defs><path mask="url(#SVGtMBvKcON)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:like" {...props}></Icon>
