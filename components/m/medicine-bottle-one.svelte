<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/m-fj4wzol.css';
import '../../css/b/buzi5ibmp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJYk3bc6W"><g class="v3_i3wktz"><path class="m-fj4wzol"/><path class="buzi5ibmp"/></g></mask></defs><path mask="url(#SVGJYk3bc6W)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:medicine-bottle-one" {...props}></Icon>
