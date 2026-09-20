<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqv3zxbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pqv3zxbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-alarm-2-solid" {...props}></Icon>
