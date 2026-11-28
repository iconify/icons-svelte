<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf9tlotji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf9tlotji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rotate-ccw-solid" {...props}></Icon>
