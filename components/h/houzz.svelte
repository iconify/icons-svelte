<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uym9oabze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="uym9oabze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:houzz" {...props}></Icon>
