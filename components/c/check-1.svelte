<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqyhy9bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqyhy9bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:check-1" {...props}></Icon>
