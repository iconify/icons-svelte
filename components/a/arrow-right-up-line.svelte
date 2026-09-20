<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpvv030jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpvv030jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-up-line" {...props}></Icon>
