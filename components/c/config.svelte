<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/t/txwygjb8d.css';
import '../../css/w/wyahbkbgb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXSFC601V"><g class="ufeehvblu"><path class="txwygjb8d"/><path class="wyahbkbgb"/></g></mask></defs><path mask="url(#SVGXSFC601V)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:config" {...props}></Icon>
