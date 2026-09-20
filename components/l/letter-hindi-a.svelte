<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ua-8bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ua-8bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:letter-hindi-a" {...props}></Icon>
