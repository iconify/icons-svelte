<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms1ustbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms1ustbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:exclamation-triangle" {...props}></Icon>
