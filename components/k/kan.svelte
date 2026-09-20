<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxr4hec5a.css';
import '../../css/z/zwxltobxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uxr4hec5a"/><path class="zwxltobxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kan" {...props}></Icon>
