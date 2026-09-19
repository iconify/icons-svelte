<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9xxmqbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9xxmqbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bomb-filled" {...props}></Icon>
