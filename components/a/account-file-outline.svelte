<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st2yjobkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st2yjobkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-file-outline" {...props}></Icon>
