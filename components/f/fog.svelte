<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p81y391ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="p81y391ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:fog" {...props}></Icon>
