<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krf8ry-1i.css';
import '../../css/a/ath_e_b-t.css';
import '../../css/g/gikp8uczy.css';
import '../../css/d/dbbzvkbuh.css';
import '../../css/q/qf57gfbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="krf8ry-1i"/><path class="ath_e_b-t"/><path class="gikp8uczy"/><path class="dbbzvkbuh"/><path class="qf57gfbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moped-20" {...props}></Icon>
