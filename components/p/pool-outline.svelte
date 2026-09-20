<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdwyfcb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mdwyfcb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pool-outline" {...props}></Icon>
