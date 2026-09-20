<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl006ob9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl006ob9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:devrant" {...props}></Icon>
