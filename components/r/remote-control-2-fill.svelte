<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-3ufwfkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-3ufwfkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remote-control-2-fill" {...props}></Icon>
