<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lln4j2bfx.css';
import '../../css/m/m7erot3eb.css';
import '../../css/h/humhrf4wy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGu0sYleFi"><g class="ft5dv1b6b"><path class="lln4j2bfx"/><path class="m7erot3eb"/><path class="humhrf4wy"/></g></mask></defs><path mask="url(#SVGu0sYleFi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:birthday-cake" {...props}></Icon>
