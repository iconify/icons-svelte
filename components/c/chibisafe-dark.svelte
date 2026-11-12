<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnm87zbsi.css';
import '../../css/j/jpb4tzbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fnm87zbsi"/><path class="jpb4tzbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chibisafe-dark" {...props}></Icon>
