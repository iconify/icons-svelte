<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoeatstfv.css';
import '../../css/l/l06m6xpen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoeatstfv"/><path class="l06m6xpen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:airplay-filled" {...props}></Icon>
