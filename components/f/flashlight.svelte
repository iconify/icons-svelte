<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fjagq7bdj.css';
import '../../css/y/ydqauvg5t.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgfK5ncmj"><g class="v3_i3wktz"><path class="fjagq7bdj"/><path class="ydqauvg5t"/></g></mask></defs><path mask="url(#SVGgfK5ncmj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:flashlight" {...props}></Icon>
