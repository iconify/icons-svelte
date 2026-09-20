<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v032modtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v032modtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:discord-fill-24" {...props}></Icon>
