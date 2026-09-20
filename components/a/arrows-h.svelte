<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5tmblb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5tmblb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-h" {...props}></Icon>
