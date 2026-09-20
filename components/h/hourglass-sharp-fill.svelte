<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saeb17b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saeb17b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hourglass-sharp-fill" {...props}></Icon>
