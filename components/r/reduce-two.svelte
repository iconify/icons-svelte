<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fbxmsfbue.css';
import '../../css/j/jnwbj5b5e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9SnDx6Nc"><g class="ft5dv1b6b"><rect class="fbxmsfbue"/><path class="jnwbj5b5e"/></g></mask></defs><path mask="url(#SVG9SnDx6Nc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:reduce-two" {...props}></Icon>
