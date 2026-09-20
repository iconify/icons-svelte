<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-5x3pb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-5x3pb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:css3-filled" {...props}></Icon>
