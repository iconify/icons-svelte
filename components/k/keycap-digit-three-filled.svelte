<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze28hzlyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ze28hzlyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-three-filled" {...props}></Icon>
