<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cflksfbjj.css';
import '../../css/n/n6jmq3bew.css';
import '../../css/j/jjq0_1y_y.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdz1AHbsC"><g class="ft5dv1b6b"><path class="cflksfbjj"/><path class="n6jmq3bew"/><path class="jjq0_1y_y"/></g></mask></defs><path mask="url(#SVGdz1AHbsC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:play-volleyball" {...props}></Icon>
