<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/i/io1qadzfc.css';
import '../../css/d/d59gqabzx.css';
import '../../css/t/trq0gv3dc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMLsYnb9M"><g class="wwvp95byt"><path class="io1qadzfc"/><circle class="d59gqabzx"/><path class="trq0gv3dc"/></g></mask></defs><path mask="url(#SVGMLsYnb9M)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:big-clock" {...props}></Icon>
