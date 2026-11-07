<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/i/ihytzob7q.css';
import '../../css/a/a06xqyb5h.css';
import '../../css/u/uggadp-bv.css';
import '../../css/a/adh5jlbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="ihytzob7q"/><path class="a06xqyb5h"/><path class="uggadp-bv"/><path class="adh5jlbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-bold-duotone" {...props}></Icon>
