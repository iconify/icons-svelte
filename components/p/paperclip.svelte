<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4q4os5vq.css';
import '../../css/u/u3riikbtv.css';
import '../../css/x/xnpcv3jbg.css';
import '../../css/p/pspmmnb4w.css';
import '../../css/e/eac3i3b4m.css';
import '../../css/c/chf58z4nv.css';
import '../../css/a/azqeltbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4q4os5vq wm-shadow"/><path class="u3riikbtv"/><path class="xnpcv3jbg"/><path class="pspmmnb4w"/><path class="eac3i3b4m"/><path class="chf58z4nv wm-shine"/><path class="azqeltbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-plush:paperclip" {...props}></Icon>
