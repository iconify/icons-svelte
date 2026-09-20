<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk4-s9iov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk4-s9iov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:emergency-call-remix" {...props}></Icon>
