<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bco27yqdx.css';
import '../../css/d/dwfg7kbwe.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCgko6bsd"><g class="wwvp95byt"><path class="bco27yqdx"/><path class="dwfg7kbwe"/></g></mask></defs><path mask="url(#SVGCgko6bsd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:exchange-two" {...props}></Icon>
