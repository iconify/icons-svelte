<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwz8-ybjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwz8-ybjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-right" {...props}></Icon>
