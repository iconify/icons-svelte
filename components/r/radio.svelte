<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgc7bi6_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgc7bi6_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:radio" {...props}></Icon>
