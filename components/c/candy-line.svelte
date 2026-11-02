<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzr7x7b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzr7x7b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candy-line" {...props}></Icon>
