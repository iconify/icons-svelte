<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfcb48v_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="qfcb48v_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:image-portrait" {...props}></Icon>
