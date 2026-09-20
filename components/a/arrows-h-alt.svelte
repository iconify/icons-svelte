<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl0-7sbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0-7sbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-h-alt" {...props}></Icon>
