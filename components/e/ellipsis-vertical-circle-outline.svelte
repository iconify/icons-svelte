<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuejpjjmz.css';
import '../../css/r/r6fga5szw.css';
import '../../css/u/ualmvtb9v.css';
import '../../css/l/lsg5j7ibl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuejpjjmz"/><circle class="r6fga5szw"/><circle class="ualmvtb9v"/><path class="lsg5j7ibl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ellipsis-vertical-circle-outline" {...props}></Icon>
