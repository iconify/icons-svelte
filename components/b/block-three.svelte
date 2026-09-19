<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up0-o6tjm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzJgSle4O"><path class="up0-o6tjm"/></mask></defs><path mask="url(#SVGzJgSle4O)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-three" {...props}></Icon>
