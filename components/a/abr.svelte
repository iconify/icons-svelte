<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t38kseb5u.css';
import '../../css/a/ahikl4b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t38kseb5u"/><path class="ahikl4b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:abr" {...props}></Icon>
