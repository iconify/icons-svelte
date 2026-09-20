<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuw7l6b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuw7l6b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mbox" {...props}></Icon>
