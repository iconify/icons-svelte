<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtad049vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtad049vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microbit" {...props}></Icon>
