<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpa-elmkg.css';
import '../../css/t/tvrv_ebup.css';
import '../../css/a/a0cnkibtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpa-elmkg"/><path class="tvrv_ebup"/><path class="a0cnkibtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-sudoku" {...props}></Icon>
