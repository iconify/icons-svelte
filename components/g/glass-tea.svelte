<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpyuubbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpyuubbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:glass-tea" {...props}></Icon>
