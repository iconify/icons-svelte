<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw9l6le0j.css';
import '../../css/a/anxy77bbg.css';
import '../../css/k/kqaej-b1t.css';
import '../../css/d/d_0yy4b_u.css';
import '../../css/z/zg9do0e_c.css';
import '../../css/b/b45rzebkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9l6le0j wm-shadow"/><path class="anxy77bbg wm-k"/><path class="kqaej-b1t wm-k"/><path class="d_0yy4b_u wm-k"/><path class="wm-k zg9do0e_c"/><path class="b45rzebkg wm-shine"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:circle" {...props}></Icon>
