<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5w3vbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5w3vbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid" {...props}></Icon>
