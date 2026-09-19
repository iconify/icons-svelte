<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_4g7047h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_4g7047h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earth-africa-europe" {...props}></Icon>
