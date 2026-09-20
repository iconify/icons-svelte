<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keo41gkck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="keo41gkck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:parking-garage" {...props}></Icon>
