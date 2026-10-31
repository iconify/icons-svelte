<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1ich61cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ich61cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:group-fill-round" {...props}></Icon>
