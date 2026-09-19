<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0j-_5b5v.css';
import '../../css/b/bcn_4bbos.css';
import '../../css/e/ekzzdgb2f.css';
import '../../css/k/k4-cxey3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l0j-_5b5v"/><path class="bcn_4bbos"/><path class="ekzzdgb2f"/><path class="k4-cxey3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:join-full" {...props}></Icon>
