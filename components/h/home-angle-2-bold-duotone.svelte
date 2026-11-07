<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gswtq35or.css';
import '../../css/e/ewx6owlel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gswtq35or"/><path clip-rule="evenodd" class="ewx6owlel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-angle-2-bold-duotone" {...props}></Icon>
