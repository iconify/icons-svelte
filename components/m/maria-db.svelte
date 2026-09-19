<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh20qccmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh20qccmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:maria-db" {...props}></Icon>
