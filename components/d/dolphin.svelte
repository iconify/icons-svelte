<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x65kp3cdr.css';
import '../../css/s/sg6tecbtd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIDphUdDF"><g class="ft5dv1b6b"><path class="x65kp3cdr"/><circle class="sg6tecbtd"/></g></mask></defs><path mask="url(#SVGIDphUdDF)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:dolphin" {...props}></Icon>
