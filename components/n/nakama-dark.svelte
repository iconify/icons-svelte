<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjio485oq.css';
import '../../css/j/j96szjbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjio485oq"/><path class="j96szjbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nakama-dark" {...props}></Icon>
