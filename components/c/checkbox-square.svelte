<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9lfmybtd.css';
import '../../css/g/g6owz749s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9lfmybtd"/><path class="g6owz749s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:checkbox-square" {...props}></Icon>
