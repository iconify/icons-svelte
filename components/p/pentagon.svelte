<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ori6x2u_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ori6x2u_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:pentagon" {...props}></Icon>
