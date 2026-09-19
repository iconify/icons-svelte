<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l15u55g8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="l15u55g8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:discover" {...props}></Icon>
