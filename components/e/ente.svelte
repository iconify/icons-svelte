<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf8cc9bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf8cc9bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ente" {...props}></Icon>
