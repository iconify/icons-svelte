<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg9bjq-ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg9bjq-ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-progress-x-sharp-fill" {...props}></Icon>
