<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6xvpbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="th6xvpbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nested-hearts" {...props}></Icon>
