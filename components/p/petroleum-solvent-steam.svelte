<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqkvepb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqkvepb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:petroleum-solvent-steam" {...props}></Icon>
