<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvclatlmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvclatlmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-02" {...props}></Icon>
