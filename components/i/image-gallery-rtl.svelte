<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpfg3lbzb.css';
import '../../css/g/g26fkqble.css';
import '../../css/p/px4i0s1qf.css';
import '../../css/l/lk2oa9bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rpfg3lbzb"/><path class="g26fkqble"/><path class="px4i0s1qf"/><circle class="lk2oa9bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-gallery-rtl" {...props}></Icon>
