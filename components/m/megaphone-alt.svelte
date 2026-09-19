<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqnw13lvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqnw13lvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:megaphone-alt" {...props}></Icon>
