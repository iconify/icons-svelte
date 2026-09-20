<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xye7cnqaq.css';
import '../../css/j/j06c4gncv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xye7cnqaq"/><path class="j06c4gncv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:arc" {...props}></Icon>
