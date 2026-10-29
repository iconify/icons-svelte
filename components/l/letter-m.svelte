<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myov-zfri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myov-zfri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-m" {...props}></Icon>
