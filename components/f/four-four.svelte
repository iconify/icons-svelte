<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlbfa8bqm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGl2MrYbix"><path class="vlbfa8bqm"/></mask></defs><path mask="url(#SVGl2MrYbix)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:four-four" {...props}></Icon>
