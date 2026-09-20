<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj229s22e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj229s22e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:friendica-fill" {...props}></Icon>
