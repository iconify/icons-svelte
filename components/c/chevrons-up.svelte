<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4_cu0b4c.css';
import '../../css/f/fvtev__4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_cu0b4c"/><path class="fvtev__4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevrons-up" {...props}></Icon>
