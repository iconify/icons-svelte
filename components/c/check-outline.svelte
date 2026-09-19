<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd4oa2b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd4oa2b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:check-outline" {...props}></Icon>
