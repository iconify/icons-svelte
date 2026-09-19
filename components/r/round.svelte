<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2stgebyp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4yRl9bjc"><circle class="z2stgebyp"/></mask></defs><path mask="url(#SVG4yRl9bjc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:round" {...props}></Icon>
