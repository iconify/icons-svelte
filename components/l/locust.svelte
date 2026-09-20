<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wldwxib8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wldwxib8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:locust" {...props}></Icon>
