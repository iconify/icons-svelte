<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zncj4gwdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zncj4gwdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-left-02" {...props}></Icon>
