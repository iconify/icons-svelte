<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za8-4ob-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za8-4ob-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:artemide-nessino" {...props}></Icon>
