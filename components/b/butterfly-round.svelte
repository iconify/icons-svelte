<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyze3kg5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyze3kg5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:butterfly-round" {...props}></Icon>
