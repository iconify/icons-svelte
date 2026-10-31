<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt4xytbyt.css';
import '../../css/r/r0k-ltjjw.css';
import '../../css/d/dz--kkbng.css';
import '../../css/k/k40zmxb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="tt4xytbyt"/><path class="r0k-ltjjw"/><path class="dz--kkbng"/><path class="k40zmxb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:gambia" {...props}></Icon>
