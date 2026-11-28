<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te3bg7bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te3bg7bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pentagon-solid" {...props}></Icon>
