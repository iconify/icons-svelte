<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsb9vacax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsb9vacax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bot-minus" {...props}></Icon>
