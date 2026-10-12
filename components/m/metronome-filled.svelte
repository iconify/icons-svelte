<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3yjsomuv.css';
import '../../css/m/msszb5b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3yjsomuv"/><path class="msszb5b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:metronome-filled" {...props}></Icon>
