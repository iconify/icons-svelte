<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w-loasbnk.css';
import '../../css/a/avm801z_y.css';
import '../../css/y/y467enbsf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzvdhfcNc"><g class="ft5dv1b6b"><circle class="w-loasbnk"/><circle transform="matrix(-1 0 0 1 24 24)" class="avm801z_y"/><path class="y467enbsf"/></g></mask></defs><path mask="url(#SVGzvdhfcNc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:auto-focus" {...props}></Icon>
