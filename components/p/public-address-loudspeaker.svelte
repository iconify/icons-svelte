<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd9xvfbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kd9xvfbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:public-address-loudspeaker" {...props}></Icon>
