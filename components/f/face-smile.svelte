<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3wc6b4ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3wc6b4ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-smile" {...props}></Icon>
