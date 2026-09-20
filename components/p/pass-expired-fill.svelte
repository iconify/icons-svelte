<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahso_0mfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahso_0mfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pass-expired-fill" {...props}></Icon>
