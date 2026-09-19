<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p84hqbcae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p84hqbcae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-eating-melon" {...props}></Icon>
