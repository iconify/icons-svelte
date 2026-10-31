<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1npqbinw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1npqbinw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-span-gloss" {...props}></Icon>
