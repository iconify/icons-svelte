<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sexcl-g3a.css';
import '../../css/e/ekk1g4byl.css';
import '../../css/l/lw-5wybjf.css';
import '../../css/i/isb5rmbbx.css';
import '../../css/k/kaeozsbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sexcl-g3a"/><path class="ekk1g4byl"/><path class="lw-5wybjf"/><path class="isb5rmbbx"/><path class="kaeozsbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moped-48" {...props}></Icon>
