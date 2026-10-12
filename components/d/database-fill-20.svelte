<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp_ciybgk.css';
import '../../css/k/k-_lh2bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mp_ciybgk"/><path class="k-_lh2bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:database-fill-20" {...props}></Icon>
