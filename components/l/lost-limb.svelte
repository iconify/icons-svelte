<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug78cmbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ug78cmbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lost-limb" {...props}></Icon>
