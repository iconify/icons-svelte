<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9daw9k4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9daw9k4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dna-remix" {...props}></Icon>
