<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztd9aub4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztd9aub4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-disabled-02" {...props}></Icon>
