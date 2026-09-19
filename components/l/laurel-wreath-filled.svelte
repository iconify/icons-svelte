<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvby8_i7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvby8_i7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laurel-wreath-filled" {...props}></Icon>
