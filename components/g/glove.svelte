<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy3qev87z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrN7KDbir"><path class="fy3qev87z"/></mask></defs><path mask="url(#SVGrN7KDbir)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:glove" {...props}></Icon>
