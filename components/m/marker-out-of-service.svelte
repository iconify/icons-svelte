<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brroz7b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brroz7b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:marker-out-of-service" {...props}></Icon>
