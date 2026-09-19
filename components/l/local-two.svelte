<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylrso7y3c.css';
import '../../css/y/yzgcxqb4r.css';
import '../../css/v/v57r1kbjg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlUt0ucDS"><g class="ylrso7y3c"><path class="yzgcxqb4r"/><path class="v57r1kbjg"/></g></mask></defs><path mask="url(#SVGlUt0ucDS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:local-two" {...props}></Icon>
