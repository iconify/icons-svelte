<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uulbojbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uulbojbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-a-box-outline" {...props}></Icon>
