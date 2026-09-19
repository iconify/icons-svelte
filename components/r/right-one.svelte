<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp-o-80fw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoo1xZdsi"><path class="hp-o-80fw"/></mask></defs><path mask="url(#SVGoo1xZdsi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:right-one" {...props}></Icon>
