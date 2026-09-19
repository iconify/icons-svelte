<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqb-39bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqb-39bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:moustache" {...props}></Icon>
