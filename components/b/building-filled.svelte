<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlmneqbga.css';
import '../../css/o/o5_ykjx1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlmneqbga"/><path class="o5_ykjx1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:building-filled" {...props}></Icon>
