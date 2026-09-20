<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcw_m1lcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcw_m1lcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mambaui" {...props}></Icon>
