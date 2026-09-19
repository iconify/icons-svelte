<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k327wib4f.css';
import '../../css/t/t6tpgmbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k327wib4f"/><path class="t6tpgmbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fork-repo" {...props}></Icon>
