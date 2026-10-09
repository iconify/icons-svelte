<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_chr5qqn.css';
import '../../css/b/bxqwznb6j.css';
import '../../css/q/q5_trsb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u_chr5qqn"/><path class="bxqwznb6j"/><path class="q5_trsb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desk-lamp-48-bold" {...props}></Icon>
