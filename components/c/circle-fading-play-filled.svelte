<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arhhw8bcu.css';
import '../../css/a/aiztnfbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arhhw8bcu"/><path class="aiztnfbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-fading-play-filled" {...props}></Icon>
