<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o2gaz3blc.css';
import '../../css/g/g163uejcd.css';
import '../../css/r/r2e8nk8aq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz6N0LYik"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="o2gaz3blc"/><path class="g163uejcd"/><path class="r2e8nk8aq"/></g></mask></defs><path mask="url(#SVGz6N0LYik)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:germs" {...props}></Icon>
