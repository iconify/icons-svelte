<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4mj_fbgb.css';
import '../../css/t/t7asixbbp.css';
import '../../css/f/fc-crnldr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0AnyqdZV"><g class="ft5dv1b6b"><path class="g4mj_fbgb"/><path class="t7asixbbp"/><path class="fc-crnldr"/></g></mask></defs><path mask="url(#SVG0AnyqdZV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:edit-movie" {...props}></Icon>
