<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6pye4bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6pye4bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:doctor-02" {...props}></Icon>
