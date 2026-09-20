<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt9wrr88u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt9wrr88u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:forecastcloud-moon-tear" {...props}></Icon>
