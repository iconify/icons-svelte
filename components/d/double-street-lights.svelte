<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trn51nbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trn51nbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:double-street-lights" {...props}></Icon>
