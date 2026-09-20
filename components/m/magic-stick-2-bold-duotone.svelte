<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kma6xtbjg.css';
import '../../css/r/rf5dcqbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kma6xtbjg"/><path class="rf5dcqbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-stick-2-bold-duotone" {...props}></Icon>
