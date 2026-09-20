<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyqqu5bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tyqqu5bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:fast-food-14" {...props}></Icon>
