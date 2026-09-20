<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl-rah09q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl-rah09q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fujitsu" {...props}></Icon>
