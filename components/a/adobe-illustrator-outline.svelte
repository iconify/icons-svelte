<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6yrczefu.css';
import '../../css/r/r-t_bpbcz.css';
import '../../css/d/daxtkab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6yrczefu"/><path clip-rule="evenodd" class="r-t_bpbcz"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-illustrator-outline" {...props}></Icon>
