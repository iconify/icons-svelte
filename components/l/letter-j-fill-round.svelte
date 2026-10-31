<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg3p42byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg3p42byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-j-fill-round" {...props}></Icon>
