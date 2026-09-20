<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctkzpqbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctkzpqbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lighting-circle-filled" {...props}></Icon>
