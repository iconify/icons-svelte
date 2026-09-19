<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inq66m2pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inq66m2pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pizza" {...props}></Icon>
