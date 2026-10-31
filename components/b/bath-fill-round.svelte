<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj1ylbb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1ylbb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bath-fill-round" {...props}></Icon>
