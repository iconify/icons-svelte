<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi01opbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi01opbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:eye-off" {...props}></Icon>
