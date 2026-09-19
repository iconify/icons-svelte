<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_2i8ot7h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUuGtqhHU"><path class="o_2i8ot7h"/></mask></defs><path mask="url(#SVGUuGtqhHU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:five-five" {...props}></Icon>
