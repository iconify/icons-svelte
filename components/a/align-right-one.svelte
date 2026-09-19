<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/g/g5oougblb.css';
import '../../css/y/y31--wboh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6dRdjcVe"><g class="hv130ab-t"><path class="g5oougblb"/><path class="y31--wboh"/></g></mask></defs><path mask="url(#SVG6dRdjcVe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:align-right-one" {...props}></Icon>
