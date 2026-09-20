<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbdkfp3ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbdkfp3ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-up-light" {...props}></Icon>
