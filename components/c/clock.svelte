<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm_fzdbbs.css';
import '../../css/g/gzm0_xb-h.css';
import '../../css/e/ev2wzjerc.css';
import '../../css/q/qa0kplb8m.css';
import '../../css/b/bwdpl5zyw.css';
import '../../css/u/u3apw6wjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="xm_fzdbbs"/><circle class="gzm0_xb-h"/><path class="ev2wzjerc"/><path class="qa0kplb8m"/><circle class="bwdpl5zyw"/><circle class="u3apw6wjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:clock" {...props}></Icon>
