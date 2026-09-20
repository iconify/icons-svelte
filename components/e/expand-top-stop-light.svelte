<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc59-q_ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc59-q_ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-top-stop-light" {...props}></Icon>
