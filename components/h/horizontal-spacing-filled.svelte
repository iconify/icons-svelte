<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clh07fbwo.css';
import '../../css/h/hhq74abkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clh07fbwo"/><rect class="hhq74abkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-spacing-filled" {...props}></Icon>
