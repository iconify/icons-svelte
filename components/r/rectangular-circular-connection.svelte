<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fobtc1bdc.css';
import '../../css/n/n_jh6lbfx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZh3QTFPY"><g class="v3_i3wktz"><path class="fobtc1bdc"/><path class="n_jh6lbfx"/></g></mask></defs><path mask="url(#SVGZh3QTFPY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rectangular-circular-connection" {...props}></Icon>
