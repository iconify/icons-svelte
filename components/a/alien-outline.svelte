<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrfmtbbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrfmtbbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alien-outline" {...props}></Icon>
