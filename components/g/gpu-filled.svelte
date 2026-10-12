<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkeen_bhs.css';
import '../../css/f/f583e5b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkeen_bhs"/><path clip-rule="evenodd" class="f583e5b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gpu-filled" {...props}></Icon>
