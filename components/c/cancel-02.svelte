<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzu44ubyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzu44ubyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cancel-02" {...props}></Icon>
