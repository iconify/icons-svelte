<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7o7vzk5e.css';
import '../../css/j/j-89n_bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7o7vzk5e"/><path class="j-89n_bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:drum-filled" {...props}></Icon>
