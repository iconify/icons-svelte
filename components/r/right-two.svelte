<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhfn9yzfo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYCI0xe9j"><path class="jhfn9yzfo"/></mask></defs><path mask="url(#SVGYCI0xe9j)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:right-two" {...props}></Icon>
