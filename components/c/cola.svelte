<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jlnr15bxu.css';
import '../../css/i/i5-ng-btb.css';
import '../../css/t/tbfk-_6ot.css';
import '../../css/l/l-90x2_qh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGps2vrDJY"><g class="s9cl3zbei"><path class="jlnr15bxu"/><path class="i5-ng-btb"/><path class="tbfk-_6ot"/><path class="l-90x2_qh"/></g></mask></defs><path mask="url(#SVGps2vrDJY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:cola" {...props}></Icon>
