<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-_ohbfa.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwvM9ld2t"><path class="zw-_ohbfa"/></mask></defs><path mask="url(#SVGwvM9ld2t)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:come" {...props}></Icon>
