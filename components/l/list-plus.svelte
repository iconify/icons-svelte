<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xljt9gbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xljt9gbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-plus" {...props}></Icon>
