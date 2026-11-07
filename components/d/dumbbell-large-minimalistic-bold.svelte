<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si5z23b4a.css';
import '../../css/b/b17et-bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si5z23b4a"/><path clip-rule="evenodd" class="b17et-bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-large-minimalistic-bold" {...props}></Icon>
