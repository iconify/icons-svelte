<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arzfajbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arzfajbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlecloudspanner" {...props}></Icon>
