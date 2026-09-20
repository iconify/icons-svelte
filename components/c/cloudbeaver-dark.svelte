<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dri0rl5gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dri0rl5gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudbeaver-dark" {...props}></Icon>
