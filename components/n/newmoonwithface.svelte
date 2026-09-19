<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al0zveb0a.css';
import '../../css/a/ayfs0cb5s.css';
import '../../css/j/jy90cd2id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="al0zveb0a"/><path class="ayfs0cb5s"/><path class="jy90cd2id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:newmoonwithface" {...props}></Icon>
