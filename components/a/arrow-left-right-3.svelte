<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swa1uqbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swa1uqbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-right-3" {...props}></Icon>
