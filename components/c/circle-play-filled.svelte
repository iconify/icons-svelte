<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud2z5r7ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ud2z5r7ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-play-filled" {...props}></Icon>
