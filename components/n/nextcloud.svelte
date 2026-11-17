<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-fbe-bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-fbe-bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nextcloud" {...props}></Icon>
