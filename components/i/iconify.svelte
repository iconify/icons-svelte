<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-3cnqbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3cnqbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:iconify" {...props}></Icon>
