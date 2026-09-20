<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fok7ss8hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fok7ss8hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-6-horizontal-fill" {...props}></Icon>
