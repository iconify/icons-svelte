<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md5jwx3_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md5jwx3_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:alarm-fill-round" {...props}></Icon>
