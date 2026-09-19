<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul4ei0bva.css';
import '../../css/o/orfhreb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="orfhreb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-alt-2" {...props}></Icon>
