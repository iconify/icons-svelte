<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj-udt_6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":655,"height":674};
const content = `<path class="mj-udt_6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:delicious" {...props}></Icon>
