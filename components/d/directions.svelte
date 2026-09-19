<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v24apqbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v24apqbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:directions" {...props}></Icon>
