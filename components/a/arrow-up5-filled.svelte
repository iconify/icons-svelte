<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wugwonb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wugwonb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up5-filled" {...props}></Icon>
