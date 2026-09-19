<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b51-lhp3z.css';
import '../../css/e/emr27z70l.css';
import '../../css/s/sv-jm2aic.css';
import '../../css/y/yibik2aeh.css';
import '../../css/l/ly-2avlcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="b51-lhp3z"/><path class="emr27z70l"/><path class="sv-jm2aic"/><path class="yibik2aeh"/><path class="ly-2avlcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:f-eight-key" {...props}></Icon>
