<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jok1bt80t.css';
import '../../css/u/uhp8mr7nr.css';
import '../../css/l/lizx6ggkd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRaw5ebJl"><g class="ft5dv1b6b"><path class="jok1bt80t"/><path class="uhp8mr7nr"/><path class="lizx6ggkd"/></g></mask></defs><path mask="url(#SVGRaw5ebJl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:arrow-keys" {...props}></Icon>
