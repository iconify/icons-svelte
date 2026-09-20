<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlo2z0biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlo2z0biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-down-bold" {...props}></Icon>
