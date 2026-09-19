<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlzckxbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":488};
const content = `<path class="hlzckxbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:qik" {...props}></Icon>
